
```bash
npm create vite@latest . --- used to install vite
```

To install react router:
 visit react router dom upgrading for other steps
```bash
npm install react-router-dom@6
npm install react-router-dom@latest
npm install react-router@latest
```

To install Tailwind css

```bash
npm install -D tailwindcss@3 postcss autoprefixer

npx tailwindcss init -p

```

Add lines           
in the tailwindconfigcss file:        

 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

In the index.css
@tailwind base;
@tailwind components;
@tailwind utilities;
