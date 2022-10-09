## Project No: 52

## Project Title: To predict the sales of weather sensitive products of Walmart during major weather events

We want to accurately predict the sales of 111 potentially weather-sensitiveproducts around the time of major weather events at 45 of their retail locations in theU.S. 

#### Dataset : https://www.kaggle.com/c/walmart-recruiting-sales-in-stormy-weather/data

The data description of all the attributes in our dataset is described as follows:
<li>Key.CSV : store_nbr, station_nbr</li>
<li>Weather.CSV: station_nbr, date, tmax, tmin, tavg, depart, dewpoint, Wetbulb-heat, heat, cool, sunrise, sunset, codesum, snowfall, preciptotal, stnpressure, sealevel, resultspeed, resultdir, avgspeed</li>
<li>‘noaa_weather_qclcd_documentation.pdf’ used for the definition of the weather data column.</li>
<li>Train.CSV: date, station_nbr, item_nbr, units</li>
<li>Test.CSV: date, station_nbr, item_nbr, units</li>
sampleSubmission.CSV: id, units</li>


#### Project files:
<li>requirements.txt - Hold information of all required libaries to execute the app</li>
<li>runtime.txt - Pyhton version for Buildpack platform detetion</li>
<li>Procfile - Gunicorn for Python HTTP server for WSGI Applications</li>
<li>model_rfr.pkl- Serialize Pyhton object which hold the model</li>
<li>app.py- API to predict the sales units</li>
<li>template-index.html- Interface for user input</li>





