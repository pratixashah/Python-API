# Weather and Vacation Analysis
 
It includes 2 API Analysis:

1. Weather - api.openweathermap.org
- WeatherPy.ipynb contains main script in Weatherpy dir.
- This script visualizes the weather of 500+ cities across the world of varying distance from the equator.
- It saves city's location and weather details in cities.csv in output_data dir
- It includes scatter charts with analysis for Temperature, Humidity, Cloudiness and Wind Speed with respect to Latitude
- This script saves all scatter plots in uotput_data dir
- This script also able to get Linear Regression Analysis for Northern and Southern Hemisphere for Temperature, Humidity, Cloudiness and Wind Speed.

2. Vacation - Google Map
- VacationPy.ipynb contains main script in VacationPy dir.
- It uses cities.csv from output_data dir for city's location and weather detail.
- It generates Heat Map on Humidity
- It also find cities having ideal weather and find hotel near to it.
- Later it plots hotels with its detail using marker on Google Map.
