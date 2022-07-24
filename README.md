# <a href="https://peygr.netlify.app/" target="_blank">Peygr</a>
![Lines of code](https://img.shields.io/tokei/lines/github/momcilovicluka/peygr)
![GitHub repo size](https://img.shields.io/github/repo-size/momcilovicluka/peygr)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/momcilovicluka/peygr)
[![GitHub Super-Linter](https://github.com/momcilovicluka/peygr/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)
[![Netlify Status](https://api.netlify.com/api/v1/badges/2a4d98f1-5cf4-4b8f-b3f3-84ab7e9bee36/deploy-status)](https://app.netlify.com/sites/peygr/deploys)

Peygr is a pager like chat app made with [React](https://reactjs.org/) and [Stream API](https://getstream.io/)

It's main intent is to be used in hospitals as a pager for doctors to communicate

* Back end is hosted on [Heroku](https://peygr.herokuapp.com/)
* Front end is hosted on [Netlify](https://peygr.netlify.app/)

# Project structure

This is the main project repo. Project is organised into two parts:
* [Client](https://github.com/momcilovicluka/peygr-front-end) (Front end)
* [Server](https://github.com/momcilovicluka/peygr-back-end) (Back end)

Both client and server are in their respective repos which have been added as submodules to this repo for easier CI with [Heroku](https://www.heroku.com/) and [Netlify](https://www.netlify.com/)

# Get Started

### `npm init -y` - Initialize the react app

### `npm install` - Install dependencies (must be done in both client (front-end) and server (back-end) folders)

### `npm start` - In the client to start it (same as node index.js)
* Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run dev` - In the server to start it (same as nodemon index.js)
* Open [http://localhost:5000](http://localhost:5000) to view it in your browser.

# Getting Started with Create React App (Automatically generated)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
