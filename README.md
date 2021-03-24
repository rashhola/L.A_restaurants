# Project_2_La_restaurants
## Restaurants in LA
![image](https://user-images.githubusercontent.com/75353991/112249468-133e8b80-8c15-11eb-9d8e-07e9de2e6f7a.png)
## Hungry Coyotes
Carolina Ibarra
Mohammed Alnaimi
Collins Tweneboah
Rasheed (Hola) Omolabi	
# Project Description
Gathered restaurant  data from LA county and yelp API. The data was transformed and loaded into a database.The purpose of this project is to understand the relationship between inspection and yelp ratings. A Data Warehouse was created to show the detailed information of yelp rating and LA county inspection rating to enable analysts to make business inferences and insight citing ratings, location, name and reviews. The data from yelp and LA county were extracted and manipulated without distorting the authenticity of the data and loaded into a database for effective querying and data analysis.
# Libraries
- Pandas
- PostgreSQL
- json
- pprint
# Assigned Tasks
- Carolina I.: responsible for scrapping LA County Inspections and Violations
- Mohammed A.: responsible for scrapping Yelp for restaurant reviews and ratings data
- Collins T: responsible for transforming and loading data SQL
- Hola: responsible for create database in SQL
# Data Sources:
Socrata Open Data API (SODA)- LA County restaurant data extracted from API and saved as .csv
- COUNTY OF LOS ANGELES RESTAURANT AND MARKET INSPECTIONS | LAC Open Data (lacounty.gov)
- https://data.lacounty.gov/Health/COUNTY-OF-LOS-ANGELES-RESTAURANT-AND-MARKET-VIOLAT/8jyd-4pv9
Yelp API
- https://www.yelp.com/developers/documentation/v3/business_search
## Process
# Extract:
-	Download 2 CSV datasets related to LA County restaurants health inspections violations
-	Collected restaurants review data using API extension via Yelp API
-	Read the data from multiple sources such as, .CSV, JSON, SQL
-	Create path ton read csv
-	Import dataset into pandas- read csv
-	The data was cleaned and filtered using pandas
# Transform:
-	The data was interpreted to determine which aspect is suitable for the project
-	A data quality check was done to determine what to clean up
-	Merge both data sets and drop columns we don’t need
-	Clean and structure the data in desired data sets
-	Post-translation data quality check was done before the data was saved to .CSV
# Load:
-	A schema was created with tables respectively
-	The .CSV files were imported into the respective tables
-	Load data into a final database that can be used for future restaurant analysis.
# Challenges
-	Limited access to Yelp API
-	Results didn’t always match, therefore created a function to match results
(109 kB)
https://user-images.githubusercontent.com/75353991/112249468-133e8b80-8c15-11eb-9d8e-07e9de2e6f7a.png
yelp.comyelp.com
Business Search Endpoint - Yelp Fusion
Yelp's API exposes search to 3rd party developers.
