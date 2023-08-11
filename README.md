# Weather App using Flet and Python

This is a simple weather mobile application developed using the Flutter framework and Python. The app allows users to input a city name and retrieve the corresponding weather information. It utilizes an API to fetch weather data and displays it using various components provided by the Flutter framework through the `flet` package.

## Demo

[![Weather App Demo](https://github.com/vikasharma005/WEATHER-APP/raw/main/235207862-0d4444e4-c968-4d80-a777-5d0b4666282d.mp4)](https://github.com/vikasharma005/WEATHER-APP/raw/main/235207862-0d4444e4-c968-4d80-a777-5d0b4666282d.mp4)


## Technologies Used

- <img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Google-flutter-logo.png" alt="Flutter Logo" height="30">
  
  - **Flutter:** Flutter is an open-source UI software development kit created by Google. It is used for building natively compiled applications for mobile, web, and desktop from a single codebase.

- <img src="https://raw.githubusercontent.com/drydart/flet/main/docs/logo.png" alt="flet Logo" height="30">
  
  - **flet:** flet is a Python package that provides a set of Flutter widgets for building user interfaces using the Python programming language.

- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Python.svg/240px-Python.svg.png" alt="Python Logo" height="30">
  
  - **Python:** Python is a versatile and widely-used programming language known for its readability and simplicity. It is used in this project to create the backend logic and interaction with APIs.

## Features

- User-friendly interface to input a city name.
- Real-time weather data retrieval using a weather API.
- Display of relevant weather information such as temperature, conditions, humidity, etc.
- Cross-platform compatibility for both Android and iOS devices.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/vikasharma005/WEATHER-APP.git
```

2. Navigate to the project directory:

```bash
cd WEATHER-APP
```

3. Install the required dependencies:

```bash
# Assuming you have Flutter and Python set up
flutter pub get
pip install flet
```

## Usage

1. Run the Flutter app on your connected device or emulator:

```bash
flet -r main.py
```

2. Input the desired city name in the app's input field and submit.

3. The app will fetch the weather data using the API and display it on the screen.

## API Usage

This app utilizes the [Weather API](https://yourweatherapi.com/) to retrieve weather data. You need to obtain an API key and replace it in the code where the API is called.

```dart
// lib/services/weather_service.dart

const String apiKey = 'YOUR_API_KEY';
const String baseUrl = 'https://api.yourweatherapi.com';

// ...
```

## Contributing

Contributions to this project are welcome! If you find any issues or want to enhance the app, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize and expand upon this template to provide more information about your project, its features, setup, and usage. Make sure to replace placeholders like `YOUR_API_KEY`, `https://yourweatherapi.com/`, and others with your actual information.
