# Just Another Text Editor

## Description

Text editors are useful tools for individuals who want to work with plain text, such as web developers. It is particularly helpful when a text editor automatically saves the user's work as they go, so that work can be accessed easily later. This Progressive Web Application is a text editor that can either be used in the browser, or downloaded and used offline. When you enter text into the editor and navigate away from it, the editor automatically saves the text you have entered for later review and use.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

This application uses a number of packages to leverage webpack, service workers, asset caching, and workbox. To install these packages, clone the repo, `cd` into it, then run the command `npm install`.

## Usage

Instructions for using the application:
- Navigate to the Just Another Text Editor application
- Enter any text you want to work with and/or save
- If you leave the page and come back, you should see the latest version of your text that you entered
- Click the "Install" button to download the application to your device

## Credits

Starter code was provided by the UC Berkeley Extension Coding Boot Camp.

The application leverages the following technologies:
- [Webpack](https://webpack.js.org/) to bundle assets
- [Babel](https://babeljs.io/) to compile the JavaScript
- [Workbox](https://developer.chrome.com/docs/workbox/) to handle service workers
- [Express](https://www.npmjs.com/package/express) to generate the server

See `/package.json`, `/client/package.json` and `/server/package.json` for the full list of packages used.

## License

MIT License