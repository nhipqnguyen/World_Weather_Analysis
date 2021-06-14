# World Weather Analysis
# Project Overview
Our task is to collect and analyze weather data across cities worldwide, including to create a Pandas DataFrame with 2000 of the world's unique cities and their weather data in real time. PlanMyTrip, a travel app will use the data to recommend ideal hotels based on clients' weather preferences.

## Challenge
- We generate a set of 2,000 random latitudes and longitudes, retrieve the nearest cities, and perform an API call with the OpenWeatherMap to create a DataFrame containing the  weather data. 
- We then retrieve customer weather preferences, use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

![WeatherPy_vacation_map](https://github.com/nhipqnguyen/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

- Then, we use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations:

![WeatherPy_travel_map](https://github.com/nhipqnguyen/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

- Lastly, we create a marker layer map with a pop-up marker for each city on the itinerary.

![WeatherPy_travel_map_markers](https://github.com/nhipqnguyen/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
