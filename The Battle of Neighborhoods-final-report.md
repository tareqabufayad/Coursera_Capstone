
# Capstone Project - The Battle of Neighborhoods - Final Report

## Introduction and background

New York city is largest city in the US. New York is also the most populated city in the country. According to the “worldpopulationreview.com” web site New York population in 2019 reached 19.88 million. With such a diverse population, people from all races live in the state of New York, and different ethnic identities have make a rich culture diversity in the city. 

New York officials reports that over 200 nationalities were be a part of New York. 
With its diverse culture and nationalities, comes diverse food dishes. There are many restaurants in New York city, each belongs to different race and ethnics like middle eastern, Italian, French, German, Chinese, Indian etc.   


## Business Problem
So, as for this project, we will search, explore and visualize all borough and neighborhoods that has great middle eastern food and dishes.

## Data Description
We will use the following data sets for this capstone project:
 - New York city data sets that contains list of countries, neighborhoods along with their latitude and longitude
    - Data Set: https://cocl.us/new_york_dataset
    - Data Description: This data set is a json file contains boroughs and neighborhoods of New York city. We use this data to dive and explore different neighborhoods in New York city 
        
 - Foursquare API data
   - Data Set: Foursquare API
   - Data Description: we will use this Foursquare API to fetch all venues and places in each neighborhood. By filtering the results and get only middle eastern restaurants


  - GeoSpace Data
    - Data Set: https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm
    - Data Description: using this data to create a choropleth map New York borough boundary. This map will visualize the results of top middle east restaurants in New York neighborhoods  



## How we will use the data (Our Approach or work methodology)
The following steps shows our work flow:
-	Fetching and storing the new York city data set from https://cocl.us/new_york_dataset
-	Using API Foursquare to explore and find all Venus for each neighborhood
-	Filtering the API Foursquare results to contain only Middle east results
-	Searching for tips, ratings and likes using API Foursquare for each result
-	Sorting the results by ratings, likes, tips and visualize these results using histogram or other suitable plotting techniques.
-	Use the Geospatial Data a Choropleth map to visualize the ranks of neighborhood using folium Python library   



```python

```
