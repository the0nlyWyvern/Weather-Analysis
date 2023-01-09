# Weather Analysis

<img src="./screenshots/wolfgang-hasselmann-unsplash.jpg" alt="Illustrate image" width="100%">

## Description

- A project in _Data Science Programming_ (University of Science HCM)
- Use Python and libraries (pandas, matplotlib) to explore the data.

## Table of Contents

1. Cleaning the data
   1. Hava a quick look on the data
   2. Drop rows with missing values
   3. Add continent column matching the country name
2. Visualize related countries & cities
3. Understanding the data
   1. Q1. List 20 cities in Europe that had lowest average temperature in December 2021.
   2. Q2. Show average temperature of one city in Vietnam in months
   3. Q3. Is there any change in average temperature in Tokyo during the time that the data was recording ?
   4. Q4. Which are ideal coastal cities for surfing ?

## Data source

Link dataset: [Historical weather data of 194 country capitals](https://www.kaggle.com/datasets/balabaskar/historical-weather-data-of-all-country-capitals?fbclid=IwAR21Wdo604qhyYh4g_p3j2r22lQIrRBAaNnw0KW2Q5mLz7LDrshPs7fx3kA "kaggle.com")  
Weather is the state of atmosphere at some point which varies in different places around the globe. Analyzing weather data can help us determine the main climate of some regions or gain some useful insights into how the weather of some specific locations have changed over years.  
This dataset comprises the daily weather data recorded in the capital of 194 countries all over the world. The data contains the following columns:

- **date** - weather data recorded date
- **country** - name of the country
- **city** - name of the city
- **Latitude** - latitude value of the city location
- **Longitude** - longitude value of the city location
- **tavg** - The average air temperature in °C
- **tmin** - The minimum air temperature in °C
- **tmax** - The maximum air temperature in °C
- **wdir** - The average wind direction in degrees (°)
- **wspd** - The average wind speed in km/h
- **pres** - The average sea-level air pressure in hPa

According to author, the data is extracted from [Meteostat](https://meteostat.net/en/) through API.

## How to use

### 1. Environment

- Jupyter Notebook
- Python-3's standard libraries and:
  - [x] Numpy
  - [x] Pandas
  - [x] Matplotlib
  - [x] Seaborn
  - [x] Geopandas
  - [x] Plotly-express
  - [x] Pycountry-convert

### 2. Order of files when running

1. ./CleaningData_Part1.ipynb
2. ./CleaningData_Part2.ipynb
3. ./VisualizeCountriesCities.ipynb
4. ./UnderstandData_Part1.ipynb
5. ./UnderstandData_Part2.ipynb

## Contributors

- Tran Tuan Kiet
- Pham Quoc Hung
