# Finance Tools

Finance Tools is a web application designed to help users manage their financial activities efficiently. Built with React, Tailwind CSS, and ShadCN UI, this project provides a modern and interactive UI for various financial operations.

## Features
- Responsive UI with Tailwind CSS
- Component-based design using ShadCN UI
- Interactive animations with Framer Motion
- Dark mode support
- Modular and scalable codebase

## Installation
To set up the project locally, follow these steps:

```sh
# Clone the repository
git clone https://github.com/yourusername/financetools.git
cd financetools

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Tailwind CSS Configuration
Ensure Tailwind is set up correctly in `tailwind.config.js`:

```js
module.exports = {
  darkMode: ["class"],
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [require("tailwindcss-animate")],
};
```

## Deployment
To deploy the project to GitHub Pages:

```sh
npm run build
npm run deploy
```

## Unable to Run npx tailwindcss init -p - "Could Not Determine Executable to Run"
$ npm install -D tailwindcss@3 postcss autoprefixer
$ npx tailwindcss init -p

## License
This project is licensed under the Indian Software License.
