## World_Weather_Analysis

In this exercise, we will use several API sources to build a travel app that allows the customer to defind their temperature preferences, which helps them narrow down on a list of destinations on a map that they are then able to select stops.  They can select mode of travel and Google Maps will mark each stop with the pertinent hotel and curent weather condition to give the user the most up-to-date weather data.

Here's what we've built:
1. We use Open Weather API and citipy to generate a list of preferred cities around the world that meets the user's temperature preferences: (ie, 65 - 85 degrees Fahrenheite). (Figure 1)
2. User select 3-4 cities of interest to focus on the destinations via Google Maps via a mode of travel.(Figure 2)
3. User is able to see for each of their stops City Name, Hotel Name, Country,Current Condition and Temperature. We used Google Maps API's info box to customize the markers.(Figure 3)

##### Figure 1: List of Preferred Cities Based on Temperature Preferences
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/100495799/170840660-4dfd4388-813f-46d2-b723-3b0ab1d05533.png)
##### Figure 2: List of Preferred Cities Route
<img width="1300" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/100495799/170840750-f50c8cf5-0c73-4500-9cdb-baadc2c7602e.png">
##### Figure 3: List of Preferred Cities with Customized Marker
<img width="841" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/100495799/170840688-170e5bf6-c8dd-49f7-9784-72794f7bd079.png">

### Tools Used
Jupyter Notebook, Python, citipy, Pandas, Matploib, Google Maps API, Google Places API, Google Directions API, OpenWeather API
