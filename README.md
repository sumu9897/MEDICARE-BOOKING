# MEDICARE-BOOKING

Create a project 
1. Create a new folder called "medicare_booking" in your workspace and open it in VS Code.
```bash
mkdir medicare_booking && code .
```
2. Inside the "medicare_booking" folder, create three more folders: "backend", "frontend".
```bash
cd medicare_booking
mkdir backend frontend
```
3. open "frontend" folder
```bash
code frontend
npm create vite@latest ./
```
4. Select a framework:
- Choose "React"
5. Select a variant:
- Choose "JavaScript"
6. Tailwind
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
7. Open `tailwind.config.js` file and add following lines to enable dark mode support:
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
8. open src>assets>index.css
Remove all and add this 
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
9. Install react dependencies
```bash
npm i react-router-dom react-icons react-spinners react-toastify swiper
```
```bash
# run
npm run dev
```
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->
<!-- ```bash
``` -->

<!-- ```bash
``` -->
<!-- ```bash
``` -->