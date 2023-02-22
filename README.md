Step 1 – Create Your Project Folder
    npm create vite@latest your-project-name -- --template react

Step 2 – Navigate to Your Project Folder
    cd your-project-name

Step 3 – Install Tailwind CSS and Other Dependencies
    npm install -D tailwindcss postcss autoprefixer

Step 4 – Generate the Configuration Files
    npx tailwindcss init -p

Step 5 – Configure Source Paths
    Add this in your content section of tailwind.config.cjs :- 
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",

Step 6 – Add Tailwind Directives to Your CSS (./src/index.css)
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

Step 7 – Start Your Vite Server
    npm run dev

Step 8 – Start Writing Tailwind CSS
