# IntelliNews

A fully automated voice-based solution that delivers the latest news. The app is designed using react, and material-UI. The backend is integrated with Alan AI to provide voice-control functionality which enables it to respond to voice input from the user as well as have a casual conversation with the client.

[www.intellinews.in](https://intellinews.netlify.app/)

## Build Status

<a href="https://travis-ci.org/standard/standard"><img src="https://img.shields.io/travis/standard/standard/master.svg" alt="travis"></a>

## Code Style

<a href="https://standardjs.com"><img src="https://img.shields.io/badge/code_style-standard-brightgreen.svg" alt="Standard - JavaScript Style Guide"></a>

## Screenshots

![image](https://user-images.githubusercontent.com/56535991/101243981-c13b2e00-3729-11eb-9e76-4dd87bc63178.png)

## Tech/Frameworks Used

**Built with**
- [React](https://reactjs.org/docs/getting-started.html)
- [Node](https://nodejs.org/dist/latest-v14.x/docs/api/)
- [Alan AI](https://alan.app/)
- [vs-code](https://code.visualstudio.com/docs)

## Installation

**Prerequisite** - Install [Node](https://nodejs.org/en/) and [VS-Code](https://code.visualstudio.com/Download) on your device.

Fork the project & fire up a terminal to enter the following command: 
```
$ git clone git@github.com:<username>/IntelliNews.git
```
cd into the project folder using:
```
$ cd ./IntelliNews/
```
To open the project in Visual Studio Code, enter:
```
$ code .
```
In the terminal, enter the following command:
```
$ npm i
```
This will install the required node modules to get you started.

Before you start the project in development mode, register on [Alan](https://alan.app/) and generate your own API key. To connect your app with Alan servers, replace the alanKey variable with your own key in the App.jsx file in the src folder. Also, copy and paste the contents of alanBackend.txt file in the src folder into your own ALAN development environment on their site.

To start the project on localhost:3000, run:
```
$ npm start
```
## How to use?

- Click/tap on the Alan button to enable it.
- Try saying anything from the cards shown on your screen.
- You can also ask Alan to read you the headlines.
- To open an article say "Open Article number" and specify the article number.
- Ask Alan to go back to the homescreen.
- You can also have a casual conversation with Alan.

## Credits

This web application is inspired by [JavaScript Mastery](https://github.com/adrianhajdin/project_news_alan_ai)

## Licence

This project is licensed under the terms of the MIT license.
