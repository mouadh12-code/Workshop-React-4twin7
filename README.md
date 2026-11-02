# Workshop React – 4TWIN7

A React workshop completed in class at **ESPRIT** (4TWIN7, academic year 2025–2026), guided by our teacher. The goal was to learn the fundamentals of React and the Vite development workflow.

> Team project carried out with [Zaineb Messaoudi](https://github.com/Zaineb-Messaoudi/workshop-react-4twin7). Original repository linked for credit.

## What I learned

- Setting up a React project with **Vite**
- Understanding the structure of a React app (`index.html`, `main.jsx`, `App.jsx`)
- Writing function components using JSX
- Managing component state with the **`useState`** hook (counter example)
- Handling events (`onClick`) and re-rendering on state change
- Using Hot Module Replacement (HMR) during development
- Linting code with **ESLint**

## Tech stack

| Tool | Version |
| --- | --- |
| React | 19 |
| Vite (rolldown-vite) | 7 |
| ESLint | 9 |
| JavaScript (JSX) | ES modules |

## Project structure

```
workshop-react-4twin7/
├── public/            # Static assets (vite.svg)
├── src/
│   ├── assets/        # Images (react.svg)
│   ├── App.jsx        # Main component (counter with useState)
│   ├── App.css        # Styles for App
│   ├── index.css      # Global styles
│   └── main.jsx       # Entry point, renders <App /> into the DOM
├── index.html         # HTML template
├── vite.config.js     # Vite configuration
├── eslint.config.js   # ESLint configuration
└── package.json       # Dependencies and scripts
```

## Getting started

**Prerequisites:** [Node.js](https://nodejs.org/) and npm.

```bash
# 1. Clone the repository
git clone https://github.com/mouadh12-code/Workshop-React-4twin7.git

# 2. Go into the project folder
cd Workshop-React-4twin7

# 3. Install dependencies
npm install

# 4. Start the development server (usually http://localhost:5173)
npm run dev
```

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Starts the development server with HMR |
| `npm run build` | Builds the app for production |
| `npm run preview` | Previews the production build locally |
| `npm run lint` | Runs ESLint on the project |

## Credits

Workshop carried out at ESPRIT School of Engineering with our teacher. Original repository by [Zaineb Messaoudi](https://github.com/Zaineb-Messaoudi/workshop-react-4twin7), used and republished here with her permission.
