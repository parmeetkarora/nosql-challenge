# nosql-challenge
Project Overview: Analyzing UK Food Establishment Ratings for "Eat Safe, Love" Magazine

The task involves working with a dataset provided by the UK Food Standards Agency to evaluate food establishment ratings. The primary objective is to assist the editors of the food magazine Eat Safe, Love in analyzing this data to guide their future articles. The project is divided into three key parts: database setup, data updates, and exploratory analysis.

Part 1: Database and Jupyter Notebook Setup

Objective: 
Import and set up the dataset in a MongoDB database, preparing the environment for further analysis.
•	Dataset Import: The data is imported from a file named establishments.json into a MongoDB database called uk_food, specifically within a collection named establishments.
•	Library Imports: Essential libraries such as PyMongo for database interactions and Pretty Print (pprint) for clear data output are imported.
•	Database Connection: A MongoDB client instance is created to establish a connection to the database.
•	Verification: The successful creation of the database and loading of the data is confirmed by listing all databases, collections, and displaying a sample document from the establishments collection.

Part 2: Database Updates
Objective: Modify the existing database by adding, updating, and deleting data based on specific requirements.
•	Addition of New Establishment: A new halal restaurant named "Penang Flavours" is added to the database with specific details like address, business type, and rating.
•	BusinessTypeID Update: The BusinessTypeID for establishments categorized as "Restaurant/Cafe/Canteen" is updated to ensure data consistency.
•	Data Removal: All establishments located in the Dover Local Authority are identified and removed from the database to keep the dataset relevant to the analysis.
•	Data Type Conversion: Certain numeric values that were originally stored as strings are converted to appropriate numeric types to facilitate accurate analysis and querying.

Part 3: Exploratory Analysis
Objective: Conduct a detailed analysis of the dataset to answer specific questions posed by Eat Safe, Love, helping the magazine editors make informed decisions.
•	Hygiene Scores Analysis: Investigate hygiene scores across various establishments to identify trends and outliers. This analysis helps in understanding which establishments maintain high standards and which ones may require further inspection.
•	Rating Values Evaluation: Examine the distribution of ratings to determine the overall quality of food establishments in different regions. This includes identifying areas with consistently high or low ratings.
•	Location-Specific Insights: Perform location-based analysis to highlight regions or specific establishments that are worth visiting or avoiding. This involves querying the dataset, displaying results, and converting data into Pandas DataFrames for easier manipulation and visualization.
•	Data Visualization: Utilize visualization techniques to present findings in a clear and compelling manner. This includes creating charts and graphs that illustrate hygiene scores, ratings distribution, and other relevant metrics.

Conclusion
The tasks performed in this project involve a combination of data manipulation, database updates, and exploratory analysis. The insights derived from this work will assist the editors of Eat Safe, Love in making informed decisions about future articles and potential restaurant visits. By carefully analyzing the food establishment ratings and related factors, the magazine can provide valuable recommendations to its readers.

