# Chicago_Restaurants_ETL

This code pulls the top 1000 restaurants in Chicago sorted by number of Yelp ratings using the Yelp API.  To access the Yelp API,
you will have to set up a config.py file with a Yelp API key.  The data is then cleansed to include only restaurants that are in Chicago (not suburbs), and the
price variable is changed to be an integer from 1 to 4.  The data is then loaded into a MongoDB database using PyMongo.