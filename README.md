
# SQLAlchemy Homework - Surfs Up!
![image](https://user-images.githubusercontent.com/57304123/89113421-c3ad1480-d425-11ea-865f-bfbec3c9f7b4.png)

This project investigates a fictional trip to Hawaii. It analyzes the weather data for Hawaii collected at various weather stations to predict typical weather during the trip. This is done in the Jupyter notebook, while a Flask app is also created that allows data calls from a SQLite database using SQLAlchemy and Flask.



## Steps
The steps followed in the analysis are:

The first step is to clean the data using Pandas notebook by removing any NAN values present in the dataset.

In this step, SQLAlchemy is used to access the sqlite database (hawaii.sqlite) available in the Resources folder. The two csv files hold the same data from the SQL database tables.

Next step is to create a weather API to do a climate analysis based on the data that was stored in the SQLite database. Using pandas dataframe. The weather data was analysed using SQLAlchemy queries and Pandas to create data frames and plotted graphs using Matplotlib.




 ![image](https://user-images.githubusercontent.com/57304123/89113460-43d37a00-d426-11ea-941f-378ab1854a8c.png)




   ![image](https://user-images.githubusercontent.com/57304123/89113494-aaf12e80-d426-11ea-9b68-ea4a5f3c659d.png)




![image](https://user-images.githubusercontent.com/57304123/89113546-7df14b80-d427-11ea-80ef-8ac8a5729267.png)

The final step was to create a Flask app to simulate the generation of api calls from a SQLite database. This application is run on the local host.

