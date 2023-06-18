# WeatherApp

WeatherApp is a simple weather application developed using HTML, CSS, and JavaScript. It allows users to get real-time weather information for a given location.

## Features

- **Current Weather:** Users can view the current weather conditions, including temperature, humidity, wind speed, and weather description.
- **Forecast:** Users can check the weather forecast for the next few days, including the maximum and minimum temperature and weather conditions.
- **Location Search:** Users can search for weather information by entering a location name or zip code.
- **Responsive Design:** The application is designed to be responsive and can adapt to different screen sizes, including desktop and mobile devices.

## Technologies Used

- **HTML:** Used to structure the web page and define the user interface elements.
- **CSS:** Used to style the user interface and make it visually appealing.
- **JavaScript:** Used to fetch weather data from an API and manipulate the DOM to update the UI dynamically.

## Getting Started

To run the WeatherApp locally on your machine, follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/niladri60/weatherApp.git
```

2. Open the project directory:

```shell
cd weatherApp
```

3. Open the `index.html` file in your preferred web browser.

4. Start exploring the WeatherApp and enter a location to get the weather information.

## API Integration

WeatherApp integrates with a weather API to fetch real-time weather data. You need to obtain an API key to use the application. Follow these steps to set up the API integration:

1. Visit the weather API provider website (e.g., OpenWeatherMap, Weatherbit, etc.) and sign up for an account.

2. Obtain an API key from the API provider. The process may vary depending on the provider. Make sure to choose an API plan that suits your needs.

3. In the `script.js` file, replace the placeholder `'YOUR_API_KEY'` with your actual API key:

```javascript
const API_KEY = 'YOUR_API_KEY';
```

4. Save the changes.

## Customization

You can customize the WeatherApp according to your preferences. Here are a few options:

- **Styling:** Modify the CSS file (`style.css`) to change the colors, fonts, or layout of the application.
- **UI Elements:** Adjust the HTML file (`index.html`) to add or remove elements from the user interface.
- **API Provider:** If you prefer a different weather API provider, you can modify the API integration code in the `script.js` file to work with the desired API.

## Contributing

Contributions to WeatherApp are welcome! If you find any bugs, have feature requests, or would like to contribute in any other way, please open an issue or submit a pull request.

## Contact

For any questions or inquiries, feel free to contact niladri60 at niladri.nandy2names@gmail.com.

Enjoy using WeatherApp!
