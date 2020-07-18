# Synxty CRA Template

Featuring husky, commitlint, commitizen and lint-staged with Airbnb code style.

**Important Note:** In order for this template to work properly you should have a git repository already created. Otherwise the installation will get stuck trying to make the initial "CRA" commit which does not respect the conventional changelog. If you're reading this note too late just cancel out of the installation and initialize a git repository.

## Description

This template is going to create a project bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and adds the following packages to the default typescript template:

- lint-staged
- husky
- cz-conventional-changelog
- cross-env
- commitizen
- eslint-config-airbnb
- styled-components
- react-router-dom
  
It also offers an opinionated structure to get started with ease:

```
src
│   index.tsx
│
└───App
│   │   App.tsx
│   │
│   
└───assets
│   
└───components
│   
└───pages
│   
└───routes
│   
└───services
│   
└───styles

```
## Instalation

Start by creating a repository for your app:

`git init my-app`

Then run the following command:

`npx create-react-app my-app --template @synxty/synxty`

And that's it!

## Available Scripts within the created project

In the project directory, you can run:

### `yarn dev` or `npm run dev`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test` or `npm run test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build` or `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject` or `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
