# home_price
This is my computer science Master's graduation project. In this project, we work on two data sets: home and university, and try to understand how universities influence the home price. A formal writing can be found in [thesis.pdf](thesis.pdf)  
  
Home table is collected over years in Hristidis's lab, and contains posts crawled from all major home selling and renting websites including Zillow, Trulia and etc. Each home entry contains information about the home including price, longitude, latitude, floor plan, zip code and etc.  
  
University table is crawled from wikipedia. It contains university information including name, longitude, latitude, enrollment, staff number and etc.  
  
The two tables are merged in [merge.ipynb](merge.ipynb). Each home is paired to the nearest university by calculating the geometric distance.  
  
We perform two types of analysis: static and time series.  
  
In static analysis, [distCorr.ipynb](distCorr.ipynb), we focus on home price from one month, and investigate how distance to the nearest university influence the home price and which type of universities has a great influence.  
  
In time series analysis, [historical.ipynb](historical.ipynb), we try to find out how do home prices change if they are close to universities compared to the homes if they are not close to universities, and if the pattern is different for different types of universities.
