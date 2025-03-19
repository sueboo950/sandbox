# Bootstrap Sandbox with Webpack and Babel

## Project Overview
This project demonstrates the setup of a Webpack-based development environment for creating a Bootstrap sandbox. The goal is to integrate Bootstrap SCSS, JavaScript, and components while leveraging Webpack, Babel, and SCSS for a modern workflow.

---

## Features
- **Modern Bundling:** Webpack and Babel for optimized JavaScript.
- **Bootstrap Integration:** Utilize SCSS and JavaScript components.
- **Styling with SCSS:** Compilation with PostCSS and Autoprefixer.
- **Hot Reloading:** Live updates via Webpack Dev Server.
- **Responsive Design:** Implementation of multiple Bootstrap components.

---

## Prerequisites
Ensure the following tools are installed:
- [Node.js](https://nodejs.org/) (v12 or higher)
- npm (comes with Node.js)

---

## Setup Instructions

### Initialize the Project
1. Start by creating a new project and initializing npm:

    npm init -y

2. Install Dependencies:
    npm install --save-dev webpack webpack-cli webpack-dev-server
    npm install --save-dev babel-loader @babel/core @babel/preset-env
    npm install --save-dev sass-loader css-loader style-loader postcss-loader autoprefixer mini-css-extract-plugin
    npm install bootstrap

3. Configure Webpack and Babel
4. Create files and file structure
5. Update package.json to open the dev server with webpack server --open in the scripts 
6. Run the dev server
