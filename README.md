# Weather App Description

This React weather app provides real-time weather information for any location. It utilizes the OpenWeatherMap API to fetch current weather and forecast data. The app consists of three main components: 
1. Search: Allows users to input a location and retrieve weather information.
2. CurrentWeather: Displays the current weather details such as temperature, humidity, and wind speed.
3. Forecast: Shows the weather forecast for the next few days.

The app makes use of the useState hook to manage the state of current weather and forecast data. When a user inputs a location, the app fetches the weather data using the fetch API and updates the state accordingly. The choice of using the OpenWeatherMap API was based on its comprehensive weather data and ease of integration.

The app is styled using CSS and follows a simple and intuitive design to provide a seamless user experience. The code is organized into separate components for reusability and maintainability. Overall, this weather app offers a user-friendly interface to access accurate and up-to-date weather information.

### To run the app: `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
