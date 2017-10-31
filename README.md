# React Starter

A personal React starter to get projects up and running quickly.
This was made in an effort to familiarize myself with modern JS build tools and configuration.

## Features

Stack includes:

* [Webpack](https://github.com/webpack/webpack) - module bundler.
* [Babel](https://github.com/babel/babel) - transpiles JSX and ES6.
* [ESLint](https://github.com/eslint/eslint) - JS validation, adhering to [Airbnb's style guide](https://github.com/airbnb/javascript).
* [PostCSS (with Autoprefixer)](https://github.com/postcss/postcss) - for parsing CSS and adding vendor prefixes.
* [Prettier](https://github.com/prettier/prettier) - set up to automatically format JSX.
* [Sass](https://github.com/sass/sass) - supported.

## Getting Started

**Clone**

```bash
git clone https://github.com/treyles/react-starter.git
cd react-starter
```

**Install**

```bash
yarn
```

## Commands

`Command`|Description
------------------|-----------
`yarn build`|Build for production.
`yarn lint`|Run ESLint to validate javascript.
`yarn format`|Run Prettier to auto format JSX.
`yarn dev`|Run webpack dev server at [http://localhost:8080/](http://localhost:8080/).