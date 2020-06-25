# NYT-Web-Scraper-
Scrapes the following NYT website: https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html

## Other resources/links used while creating the final CSV output : 
https://coronavirus-resources.esri.com/datasets/esri::bureau-of-labor-statistics-monthly-unemployment-current-14-months/data?geometry=-166.940%2C28.795%2C167.571%2C67.148&layer=1

### Purpose: 
To understand reopening policies across states in the U.S. 
### Content: 
Scraped text along with subsequent personal analysis 

## Overall Description 
The underlying structure of how this scraper works is by using a bunch of lists. Each list should contain around 52 items, 
with each item being a state. Each list is a column in the dataframe. The scraper takes advantage of the dataframe structure to fill in 1 or 0's if that specific state meets varying hard-coded conditions. The final CSV contains each state, what has industries/businesses have reopened in that state, respective political party and governor, and COVID-19 data. The main purpose of this mini-project is to understand re-opening policies, find patterns, and conduct risk assessments on existing financial customers.   

