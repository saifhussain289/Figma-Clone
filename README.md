# Figma UI Clone

A responsive web application that replicates the user interface of Figma, a popular design tool. This project showcases the implementation of key Figma UI features, built using modern web technologies.

> **Note:** This project is in its early stages of development. Some bugs or mishandling may occur as features are still being added and refined. Also this is my first project I am putting in public on github

## Features
- Responsive design that adapts to various screen sizes.
- Interactive toolbars and navigation panels similar to Figma.
- Real-time preview of UI elements and layout.
- Basic mockup and design editing features (Optional, depending on your project scope).
- Clean and user-friendly interface.

## Technologies Used
- HTML5, CSS3, JavaScript
- React (or any framework you used)
- Tailwind CSS (or other styling tools)
- (Any other relevant libraries/tools)

- figma-ui-clone/
│
├── public/               # Static assets like images, icons, etc.
├── src/                  # Source code files
│   ├── components/       # Reusable UI components (buttons, menus, etc.)
│   ├── pages/            # React pages or views
│   ├── assets/           # Images, icons, and other static resources
│   ├── styles/           # CSS/SCSS or Tailwind config files
│   └── App.js            # Main app entry point
│
├── .gitignore            # Git ignore file
├── package.json          # Project metadata and dependencies
└── README.md             # Project documentation



# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```


Known Issues
Some interactive elements may not function perfectly due to the early stage of development.

Design previews might not be fully accurate in some cases.

Performance may degrade with a large number of UI elements.

License
This project is licensed under the MIT License.
