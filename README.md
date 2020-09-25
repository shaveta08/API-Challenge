# What-s-the-Weather-Like-
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. 
So using what I've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

## Part I - WeatherPy
In this project, we'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 
To accomplish this, we'll be utilizing a simple Python library, the **OpenWeatherMap API**, and a little common sense to create a representative model of weather across world cities.
* So we have used a series of scatter plots to showcase the following relationships:
    1. Temperature (F) vs. Latitude
    2. Humidity (%) vs. Latitude
    3. Cloudiness (%) vs. Latitude
    4. Wind Speed (mph) vs. Latitude

![img-text](https://github.com/shaveta08/What-s-the-Weather-Like-/blob/master/Scatter_plots/CityLatitudeVsMaxTemp.png)![img-text](https://github.com/shaveta08/What-s-the-Weather-Like-/blob/master/Scatter_plots/CityLatitudeVsMaxHumid.png)![img-text](https://github.com/shaveta08/What-s-the-Weather-Like-/blob/master/Scatter_plots/CityLatitudeVsCloud.png) ![img-text](https://github.com/shaveta08/What-s-the-Weather-Like-/blob/master/Scatter_plots/CityLatitudeVsWindSp.png)

* Running linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

![img-text] () ![img-text] ()

Results: 
* Temprature of the cities is co-related with the latitude. Temperature is inversely related to latitude. As latitude increases, the temperature falls, and vice versa. Generally, around the world, it gets warmer towards the equator and cooler towards the poles.
* Humidity and Latitude trends in both the hemispheres are same, Liner regression shows a constant Humidity across southern and northern cities i.e. approximatly 70%.
* Trends for cloudiness with latitude is same for both the hemispheres but the cloudiness Liner regression is different, with Northern Hemisphere the value is approximatly 50 and Southern hemisphere cities has approximate value 30.
