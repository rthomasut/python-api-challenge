# Python API Challenge

## Background

Utilize Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

## Part 1: WeatherPy

Create a Python script to visualize weather data for over 500 cities at varying distances from the equator.

### Create Plots to Showcase Relationships

- Retrieve weather data using OpenWeatherMap API.
- Generate scatter plots for:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed

### Compute Linear Regression

- Calculate linear regression for each relationship.
- Create scatter plots for:
  - Northern Hemisphere: Temperature vs. Latitude
  - Southern Hemisphere: Temperature vs. Latitude
  - Northern Hemisphere: Humidity vs. Latitude
  - Southern Hemisphere: Humidity vs. Latitude
  - Northern Hemisphere: Cloudiness vs. Latitude
  - Southern Hemisphere: Cloudiness vs. Latitude
  - Northern Hemisphere: Wind Speed vs. Latitude
  - Southern Hemisphere: Wind Speed vs. Latitude

## Part 2: VacationPy

Use weather data skills to plan vacations using Jupyter notebooks, the geoViews Python library, and the Geoapify API.
- Create map with city points and humidity-based point sizes.
  - Narrow down cities based on weather conditions.
  - Use Geoapify API to find hotels.
  - Display hotel info in hover messages on map.
