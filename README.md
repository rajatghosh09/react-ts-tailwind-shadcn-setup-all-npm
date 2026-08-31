# <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="React Logo" width="25"/> React +<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="25"/> Next.js +<img src="https://vitejs.dev/logo.svg" alt="Vite Logo" width="25"/> Vite + <img src="https://raw.githubusercontent.com/remojansen/logo.ts/master/ts.png" alt="TypeScript Logo" width="25"/> TypeScript + <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Tailwind_CSS_Logo.svg" alt="Tailwind CSS Logo" width="25"/> Tailwind + shadcn/ui

A starter project using **Vite**, **React**, **Next.js**, **TypeScript**, **Tailwind CSS**, and **shadcn/ui** components.

---

## 🚀 Tech Stack

- [Vite](https://vitejs.dev/) – Fast build tool  
- [React](https://reactjs.org/) – UI library  
- [TypeScript](https://www.typescriptlang.org/) – Type safety  
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling  
- [shadcn/ui](https://ui.shadcn.com/) – Re-usable UI components  

---

## ⚙️ Installation & Setup

### 1. If you want to run a project in PowerShell using these 2 commands
```bash
cd file_name
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### 2. Create a project with Vite+React

```bash
npm create vite@latest
Select a framework:
# Select: React
Select a variant:
# Select: TypeScript
or
# Select: JavaScript
Use rolldown-vite (Experimental)?:
# Select: No
Install with npm and start now?
# Select: Yes
```

### 3. Install Tailwind CSS
```bash
npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p
```
## 🛠 Update `tailwind.config.js`
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## 🎨 Add Tailwind to `src/index.css`
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## 🎨 Install Material UI.
```bash
npm install @mui/material @emotion/react @emotion/styled @mui/icons-material
```

## 🎨 Install React-icons`
```bash
npm i react-icons
```

## 🎨 Install Lucide-React-icons`
```bash
npm i lucide-react
```

## 🎨 Install Lottie-React-Animation`
```bash
npm i lottie-react
```

## 🎨 Install Sonnar(Toster(using for sweet alert))
```bash
npm i sonner
```

## 🎨 Install Axios(using for api fetch)
```bash
npm i axios
```

## 🎨 Install db.json(start custome server)
```bash
npx json-server db.json
```

## 🎨 Install React Router Dom
```bash
npm i react-router-dom
```

## 🎨 Install React Hook Form
```bash
npm i react-hook-form
```

## 🎨 Install yup
```bash
npm i yup
```

## 🎨 Install yup-resolver
```bash
npm i @hookform/resolvers
```

## 🎨 Install JS-Cookies
```bash
npm i js-cookie @types/js-cookie
```

## 🎨 Install appWrite
```bash
npm i appwrite
```
## 🎨 Install React-Redux
```bash
npm i react-redux
```

## 🎨 Install Redux-Toolkit
```bash
npm i @reduxjs/toolkit
```

### 3. Create a project with NextJS
```bash
npx create-next-app@latest
What is your project named? ./ (if you already created a folder, then do "./" otherwise "folder name")
Would you like to use the recommended Next.js defaults?
# Select: No, customize settings
Would you like to use TypeScript?
# Select: TypeScript
or
# Select: JavaScript
Which linter would you like to use? »
# Select: ESLint
Would you like to use React Compiler?
# Select: No
Would you like to use Tailwind CSS?
# Select: No
Would you like your code inside a `src/` directory?
# Select: Yes
Would you like to use App Router? (recommended)
# Select: Yes
Would you like to customize the import alias (`@/*` by default)?
# Select: Yes
What import alias would you like configured? ... @/*
# Select: press enter
```

## 🎨 Install supabase
```bash
npm i @supabase/supabase-js
```

## 🎨 Install next-js cookies
```bash
npm i cookies-next
```

## 🎨 Install zustand
```bash
npm install zustand
```

## 🎨 Install tanstack/react-query
```bash
npm i @tanstack/react-query-devtools
```

### 🎨 Install shadcn using JS
```bash
## First install Tailwind CSS
npm install tailwindcss @tailwindcss/vite

## Replace everything in src/index.css
@import "tailwindcss";

## Now create the jsconfig.json file ans paste it
{
    "compilerOptions": {
    "paths": {
      "@/*": ["./src/*"]
    },
    "moduleResolution":"bundler"
  },
  "include":["src"]
}

## Now update vite.config.js
import tailwindcss from '@tailwindcss/vite'
import react from '@vitejs/plugin-react'
import { defineConfig } from 'vite'
import path from 'path'
import { fileURLToPath } from 'url'

const __filename = fileURLToPath(import.meta.url)
const __dirname = path.dirname(__filename)

// https://vite.dev/config/
export default defineConfig({
  plugins: [react(), tailwindcss()],
  resolve: {
    alias: {
      "@": path.resolve(__dirname, "./src"),
    },
  },
})

## Now install shadcn ui and choose
npx shadcn@latest init

√ Select a component library » Base UI (Recommended)
√ Which preset would you like to use? » Nova
```
