# World_Weather_Analysis

## Overview of Project
- We have created PlanMyTrip app which will request the customers' weather preferences and return a range of unique cities around the world where the customer can travel to have said preferences met. We will be collecting this data and use NumPy module to generate about 2,000 latitudes and longitudes, we then use citipy module to list the nearest cities we will then use OpenWeatherApp API to request weather data for each unique city in the list and parse said data from JSON to add it to a DataFrame to help us analyze the different weather characteristics per latitude such as temperature, humidity, cloudiness, wind speed, etc...

- In this challenge we will be adding weather description to the already retrieved weather data. We then will have the beta testers use the input statements to filder the data by their weather preferences which will be used to identify potential travel destination and nearby hotels. From this potential travel destinations the tester will choose four cities and create a travel itinerary and with Google Maps Directions API we will create the travel route between the four cities as well as a marker layer map for all potential destinations.

## Marker Layer Map with Potential Destinations
![marker_layer](/Vacation_Search/WeatherPy_vacation_map.png)

## Itinerary Map
![itinerary](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
![itinerary_2](/Vacation_Itinerary/WeatherPy_travel_map.png)
