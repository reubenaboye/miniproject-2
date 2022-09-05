# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
The focus of the present project was one the use of APIs to extract on POIs of our choosing and the subsequent cleaning of said data and its transfer to a local database on our system. For my project, I aimed to extract data related to food establsihements within a 1km radius of Yonge and Dundas Square in Toronto, Canada. 
## Process
### Step 1: Data Extraction
To gather establishment data on sourrounding food enterpises I made use of APIs from FourSquare and Yelp, utilizing the places and business/search endpoints respectively. This consisted of undeterking several API requests, the responses to which were, when recieved, structured into JSON formatting. I was then able to parse the data for certain POIs and merge such data into dataframes. 
### Step 2: Exploratory Data Analysis and Data Storage
The extraction and data cleaning of the previous section was followed by simple exploratory data analyses where we ordered the top 10 restaurants by their consumer rating. Afterwards, the dataframes were stored into a local dataframe via SQL. 

## Results
In comparing the two APIs, what my experience suggested was that a greater deal of detailed data on the attributes of nearby food establsihmenet was available throught YELP APIs as opposed to FourSquare, thought the latter provided a greater ease of access then Yelp did. 

## Challenges 
With respect to challenges encoutered during the process, two come to mind:
    1. Some slight struggles with the YELP APi,
    2. Syntax issues that arose in implementing SQL commands. 

The first challenge was the result of some issues when it came to the use of the API key in gaining confirming authorization. 

The second arose form trying to send SQL commands via python as was illustrated in the past week's content. Functions defined to send those commands often came across errors in syntax that were more difficult to gauge. 

## Future Goals
(what would you do if you had more time?)