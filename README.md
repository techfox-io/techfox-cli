# TechFox CLI [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green.svg)](https://github.com/techfox-io/techfox-cli/pulls)

Create apps with no build configuration.

- [Creating an App](#creating-an-app) – How to create a new app.

Create React, React Native App works on macOS, Windows, and Linux.<br>
If something doesn’t work, please [file an issue](https://github.com/techfox-io/techfox-cli/issues/new).

## Installation
```sh
npm i techfox-cli -g
```

## Quick Overview
Create new React App
```sh
techfox-cli --init-react my-app
cd my-app
```
Create new React Native App
```sh
techfox-cli --init-react-native my-app
cd my-app
```
### Get Started Immediately

You **don’t** need to config new project more, we configured smart structure and you can implement this flow.
They are preconfigured and hidden so that you can focus on the code.

Just create a project, and you’re good to go.

## Creating an App

**You’ll need to have Node 10.0 or later on your local development machine** (but it’s not required on the server). You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

To create a new app, you may choose one of the following methods:

### React

```sh
techfox-cli --init-react my-app
```
### React Native

```sh
techfox-cli --init-react-native my-app
```

It will create a directory called `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src
│   ├── components
│        └── Button
│           ├── index.js
│           └── styled.js
│   ├── modules
│       ├── Authen
|           ├── ActionTypejs
│           ├── index.js
|           ├── Model.js
|           ├── private-components
|               └── Form
|                   ├── index.js
|                   └── styled.js
│           └── styled.js
|       └── shared-components
|           └── Linear Button
|               ├── index.js
|               └── styled.js
├── App.css
├── App.js
├── App.test.js
├── index.css
├── index.js
├── logo.svg
└── serviceWorker.js
```

No configuration or complicated folder structures, just the files you need to build your app.
Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project, you can run some built-in commands:

### `npm start` or `yarn start`

Runs the app in development mode.

### `npm test` or `yarn test`

By default, runs tests related to files changed since the last commit.
The build is minified and the filenames include the hashes.
Your app is ready to be deployed.

## User Guide

You can find detailed instructions on using TechFox CLI and many tips in [its documentation](https://github.io/techfox-io/techfox-cli).

## What’s Included?

Your environment will have everything you need to build app:

- React, React Native, JSX, ES6, Flow syntax support.
- Language extras beyond ES6 like the object spread operator.
- Autoprefixed CSS, so you don’t need `-webkit-` or other prefixes.
- A fast interactive unit test runner with built-in support for coverage reporting.
- A live development server that warns about common mistakes.
- A build script to bundle JS, CSS, and images for production, with hashes and sourcemaps.
- Hassle-free updates for the above tools with a single dependency.

## Popular Alternatives

TechFox CLI is a great fit for:

- **Learning React, React Native, ...** in a comfortable and feature-rich development environment.
- **Starting new applications with smart structure easier.**

## Contributing

We'd love to have your helping hand on `techfox-cli`! See [CONTRIBUTING.md](CONTRIBUTING.md) for more information on what we're looking for and how to get started.
