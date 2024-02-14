# WeatherPy & VacationPy

## Overview
This project consists of two Python data analysis scripts: WeatherPy and VacationPy. WeatherPy analyzes weather data using the OpenWeatherMap API to provide insights into how weather conditions change as one moves away from the equator. VacationPy uses the data collected in WeatherPy, along with the Geoapify API, to help users plan their ideal vacation destinations based on weather preferences.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Credits](#credits)

## Introduction
The WeatherPy script retrieves weather data from the OpenWeatherMap API and analyzes how various weather parameters change with latitude. It generates scatter plots to visualize the relationships between latitude and temperature, humidity, cloudiness, and wind speed.

The VacationPy script utilizes the weather data collected by WeatherPy, along with the Geoapify API, to identify ideal vacation destinations based on user-defined weather preferences. It generates heatmaps to display the locations of hotels with desirable weather conditions.

## Features
- **WeatherPy:**
  - Retrieves weather data from the OpenWeatherMap API.
  - Analyzes weather parameters (temperature, humidity, cloudiness, wind speed) with respect to latitude.
  - Generates scatter plots to visualize the relationships between weather parameters and latitude.

- **VacationPy:**
  - Uses weather data collected by WeatherPy.
  - Integrates the Geoapify API to identify vacation destinations based on weather preferences.
  - Generates heatmaps to display hotel locations with desirable weather conditions.

## Requirements
- Python 3
- Pandas library
- Matplotlib library
- SciPy library
- GeoPandas library
- Folium library
- Various APIs (e.g., OpenWeatherMap, Geoapify)

**Note:** This project requires access to various APIs, such as OpenWeatherMap and Geoapify, for weather data, geographical information, and hotel recommendations. However, the API keys are not provided in this repository. You will need to obtain your own API keys and configure them accordingly in the Python scripts. Make sure to add the API keys to your `.gitignore` file to keep them secure.

APIs used in this project, visit:
- [OpenWeatherMap API](https://openweathermap.org/)
- [Geoapify API](https://www.geoapify.com/)

## How to Run
1. Open your Python environment.
2. Navigate to the project directory.
3. Open the Jupyter notebooks named `VacationPy-Analysis.ipynb` and `WeatherPy-Analysis.ipynb`.
4. Before running the scripts, create a Python source file named `api_keys.py` in the project directory to store your API keys. Inside the file, create variables named `geoapify_key` and `weather_api_key` and assign your API keys to them. For example: (geoapify_key = "YOUR_GEOAPIFY_API_KEY") & (weather_api_key = "YOUR_WEATHER_API_KEY")
5. Replace the API key in the code with your own key.
6. Create a `.gitignore` file in the project directory if one does not already exist.
7. Add the API key variable name to the `.gitignore` file to prevent it from being committed to version control.
8. Run the scripts to perform the analysis.


## Credits

### Acknowledgments
Special thanks to Berkely Data Analytics for providing code snippets and resources used in this project. UC Berkeley Extension

### Special Thanks
- Providers of the following APIs:
  - [OpenWeatherMap API](https://openweathermap.org/)
  - [Geoapify API](https://www.geoapify.com/)
- ChatGPT for providing assistance and guidance during the development of these projects.

### Source Code
Special thanks to the contributors of the UCB-VIRT-DATA-PT-11-2023-U-LOLC GitHub repository for providing valuable code and resources used in this project.
