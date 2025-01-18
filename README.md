Weather App

This is a simple weather application that provides real-time weather information for any city. The app fetches data from the OpenWeatherMap API and displays the current temperature, humidity, wind speed, and weather conditions.

Features

Search for real-time weather data by city name.

Displays temperature in Celsius, humidity, and wind speed.

Dynamically updates weather icons based on weather conditions.

Technologies Used

HTML5

CSS3

JavaScript

OpenWeatherMap API

How to Use

Clone or download the repository to your local machine.

Ensure you have an active internet connection.

Open the index.html file in your web browser.

Enter the name of a city in the search box and click the search button to view the weather information.

Project Structure

weather-app/
|-- index.html
|-- styles.css
|-- script.js
|-- images/
    |-- search.png
    |-- rain.png
    |-- clouds.png
    |-- clear.png
    |-- drizzle.png
    |-- mist.png
    |-- wind.png
    |-- humidity.png

API Key Configuration

The app uses the OpenWeatherMap API. You need to provide your own API key to make the app functional.

Replace the placeholder API key in the script section of index.html with your own:

const apiKey = "YOUR_API_KEY";

You can get your free API key by signing up at OpenWeatherMap.

Known Issues

Ensure all image files are correctly placed in the images directory.

Check for typos in weather conditions, e.g., "Drizzel" should be corrected to "Drizzle."

Case sensitivity in weather conditions can cause mismatched icons (e.g., "clouds" vs. "Clouds"). Ensure consistency when mapping icons.

Future Improvements

Add more weather details like sunrise, sunset, and weather forecast.

Support for multiple units (e.g., Fahrenheit).

Improve error handling for invalid city names.

License

This project is open-source and free to use.

Contribution

Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

Thank you for using the Weather App!

