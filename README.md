# Trip Top

An asynchronous web app built using Node.js which allows users to plan a trip to a place based on its forecasted weather data 

## Features

- Sets up server side GET & POST routes using Express
- CSS grid and flexbox are used along with Sass syntax to style elements
- Uses [Webpack](https://webpack.js.org) for asset management and optimization with separate development and production environments
- Coordinates of a place are fetched using the [Geonames API](http://www.geonames.org/export/web-services.html) based on the place entered by the user
- Weather details (a short description, weather icon, maximum temperature, and minimum temperature) are fetched using the [Weatherbit API](https://www.weatherbit.io/api/weather-forecast-16-day) which uses the coordinates and a date as input
- An optional calendar UI allows the user to select the date using [datepicker](https://github.com/qodesmith/datepicker)
- Image of the place is displayed using the [Pixabay API](https://pixabay.com/api/docs/)
- [node-fetch](https://github.com/node-fetch/node-fetch) enables to use the Fetch API syntax in the server side to solve any CORS errors
- A countdown displays the number of days left before the current date based on the date selected by the user
- Tests for server and application javascript are added using Jest
- Service Workers are added to provide offline access

## Installation and Usage

- install all project dependencies with `npm install`
- start the server with `npm start`
- open `http://localhost:8000` in your preferred browser

## License

The contents of this repository are covered under the [MIT License](LICENSE).
