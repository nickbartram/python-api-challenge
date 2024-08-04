# README for Module 6 Challenge (python-api)

## Introduction
This assignment looks draws weather data from an api and compares it to city data. It looks at how weather changes at different lattitudes.

## Data
The data comes from Openweather API, citipy, and Geoapify API. The openweather API is used to find current weather conditions in various cities, citipy is used to find data on various cities across the globe, and Geopify is used for further data about cities, specifically hotel locations

## Methodology
First we create a list of random cities from different lattitues using citipy. Then we get weather data about those cities using Openweather API. Then we create a dataframe and plot some of the weather data from those cities. Finally we find hotel data from some ideal cities and plot their geo-locations.

## Results
The results of the city weather data are mixed: some plots so a clear correlation while others do not. The ideal city geo-location plots give some interesting vacation destination ideas.

## Conclusion
It does, in fact, get warmer the closer you are to the equator. Further discussion on various data relationships in markdown cell at the bottom of WeatherPy.ipynn

## References
Class materials were used extensively for this assignment, as well as: 
- stackoverflow.com 
- Xpert Learning Assistant 
- ChatGPT.com

## Usage
WeatherPy.ipnyb can take a while query the Openweather API, best to run only once and be prepared to allow 5-10 for the query to end.