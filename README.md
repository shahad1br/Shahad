# WeatherApp
# Weather Information App

This desktop application, built on Java, offers weather information for specified locations by utilizing the OpenWeatherMap API. It presents real-time weather conditions along with an 8-day forecast. Additionally, users have the option to toggle between Celsius and Fahrenheit units and can access their search history.

## Features

- Retrieves up-to-date weather data for a chosen location.
- Shows an 8-day weather forecast.
- Enables toggling between Celsius and Fahrenheit temperature units.
- Keeps a record of search history for easy access to previously searched locations.

## Prerequisites
  
- Java Development Kit (JDK) 8 or higher.
- OpenWeatherMap API key.

## Installation

  1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/weather-app.git
cd weather-app
    ```

    2. Replace the `API_KEY` in `WeatherAPIService.java` with your OpenWeatherMap API key.
 
## Usage

1. Compile the Java files:
    ```sh
    javac WeatherApp.java WeatherAPIService.java
    ```

3. Run the application:
    ```sh
    java WeatherApp
    ```

## Class Descriptions

### `WeatherApp`

This class is responsible for building the application's GUI with Swing. It encompasses:

- `locationField` for inputting the location.
- `weatherInfoArea` for showing current weather details.
- `iconLabel` for presenting weather icons.
- `forecastLabel` for showcasing the weather forecast.
- `unitComboBox` for toggling between Celsius and Fahrenheit.
- `searchHistoryList` for listing previous searches.

### `WeatherAPIService`

This class manages API requests to the OpenWeatherMap API and features the following methods:

- `getWeather(String location)`: Retrieves current weather information for the given location.
- `getForecast(String location)`: Obtains weather forecast data for the specified location.

## Example

Here’s how to use the application:

1. Type a location (e.g., "Italy") into the text field.
2. Press the "Search" button to retrieve the weather data.
3. The current weather details will appear, showing temperature, humidity, wind speed, and overall conditions.
4. Below the current weather, you will find the weather forecast.
5. Utilize the combo box to toggle between Celsius and Fahrenheit.
6. Check the search history list for previous searches, and double-click any entry to revisit its weather information.

## Contributing

I welcome you to fork the repository and submit pull requests for enhancements and new features.

## License

This project is licensed under the MIT License.
  
