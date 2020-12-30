# Coursera_Capstone

IBM Applied Data Science Capstone Project   

## Opening a New Restaurant in London, UK

<img src='London.jpg'>


### Introduction
London is the capital and the largest city of England and the United Kingdom.  
According to Office for National Statistics, London has 201,1 restaurants per 100,000 population, which is quite high score, that show demand for restaurants.

### Business Problem
The objective of this project to analyze and select best location for a new Mediterranean food restaurant in one of the London central districts. 
Using data science methodology and machine learning techniques, this project aims to provide solutions to business problem.
In the central districts London, an investor wants to open a Mediterranean food restaurant, and looking for a location that there is little competition for business. Which location would be best for that?

### Data
The postal districts of London city will be extracted from Wikipedia.
The source page has a table with Location, London borough, Post town, Postcode district, Dial code, OS grid ref attributes.
Location, London borough and Postcode district columns will be used.

With the help of Nominatim geolocator geographical coordinates of each postal code district will be collected.

Using Foursquare API, venues will be collected by each district. 
The most common types of restaurants will be identified for each location. District latitude and longitude data will be used in order to get venue information. 
For each venue distance center, category, popularity and venue category feature will be taken into consideration.

### Methodology

	Web scraping, Identifying the neighbourhoods in central London  
	Nominatim, coordinates of districts  
	Visualizing neighbourhoods in target area  
	Foursquare API, retrieving venue information for each neighbourhood  
	Processing the data, selecting required features  
	Applying K-Means Clustering machine learning techniques.  
	Analyzing each neighbourhood and the most common restaurant type  
	Reporting the results and making recommendations.  
  
  
### Results
	According to number of restaurants for each location, Farringdon, St. Luke's are best places since they have least number of restaurants.     
	However Italian, French  and Spanish restaurants are among the most frequent in those places. Since the investor wants to open a Mediterranean restaurant, it wouldn't be profitable to start business in a competitive area. Looking at those locations closely, King's Cross is the only location that has no French, Italian, Spanish, Turkish restaurant which are parts of Mediterranean cuisine.    
	Looking at those locations closely, King's Cross is the only location that has no French, Italian, Spanish, Turkish restaurant which are parts of Mediterranean cuisine.   
	**As a conclusion, King's Cross would be the best location to start a Mediterranean Restaurant business since it is among the least that has total number of restaurant and doesn't have Mediterranean restaurants in most commons.**
