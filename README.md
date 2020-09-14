# miniType

A Minimalist Web-Server Typing Application.

# Frameworks/Libraries Used

miniType uses a variety of JS & CSS Frameworks or Libraries to operate.

Here is a list of all of them, including source links.

- [Milligram](https://milligram.io/) as the main CSS Framework to design main UI components
- [ExpressJS](https://expressjs.com/) as a NodeJS Framework for routing and port management (Back-End)
- [Random-Word-API](https://random-word-api.herokuapp.com/word?number=8) for generating random words from the dictionary for the user to type
- [ICanHazDadJoke](https://icanhazdadjoke.com/) for generating random jokes for the user to type
- JSON Data Management Algorithms for storing data for typing statistics, text statistics, etcetera

## Front-end

- The `views/` folder contains the vanilla HTML webpage content
- The `public/` folder contains the middle-end code (webpage js & css)

## Back-end

- The main back-end node-js file is `server.js`, which is where all routing/back-end data is stored

## Deploy

Site is [**minitype.herokuapp.com**](https://minitype.herokuapp.com/).

This site is deployed at [**Heroku**](https://heroku.com).

For testing, the site was originally deployed on [**Glitch**](https://glitch.com/).