# Weather Or Not

## Overview

### Problem:
The place that I live has crappy weather for the next _*n*_ days.  I have off for the next _*n*_ days and an accompanying desire to be outside for that time if possible.  Where can I feasibly go?

### Solution:
Be able to quickly see a list of all of the places that I could feasibly reach given a set of user defined variables (_location_, _distance_, _temperature_)

### Questions:
1. What variables do we want the user to be able to control
	- Location
	- Distance
		1. Do we assume driving?
		2. In miles, kilometers, hours?
	- Temperature
		1. Farenheit?
		2. Celsius?
2. Should we use an API or a database of location records and let SQL run the haversine formula on lat/long?

### Tasks:
1. Find a good weather API
	- [Wunderground API](https://www.wunderground.com/weather/api/)
2. Research computing distance from current location
	- [Haversine formula for finding nearest location](http://www.plumislandmedia.net/mysql/haversine-mysql-nearest-loc/)