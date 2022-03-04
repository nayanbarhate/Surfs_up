# Surfs_up
Using Python, SQLAlchemy, and Flask, analyze and visualize climate data as you prepare to open up a surf shop.

## Overview:
An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii.  The investor's main concern is the precipitation forcing the shop to close too frequently.  To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database. 

## Purpose
1. Explain the structures, interactions, and types of data of a provided dataset.
2. Differentiate between SQLite and PostgreSQL databases.
3. Use SQLAlchemy to connect to and query a SQLite database.
4. Use statistics like minimum, maximum, and average to analyze data.
5. Design a Flask application using data.

## Results:

1. Image of June Statistics for Temperature:

![June_temp](https://github.com/nayanbarhate/Surfs_up/blob/main/Resources/June_temp.png)

2. Image of December Statistics for Temprature:

![Dec_temp](https://github.com/nayanbarhate/Surfs_up/blob/main/Resources/Dec_temp.png)

3. Analysis of the Results:
The mean temperature for June, 75°F, is higher than the mean temperature for December, 71°F. However, the opposite is true for precipitation. December had the higher mean precipitation, 0.22 inches, while June's mean precipitation was 0.14 inches.
Here are the Images of the Graphs:

![June_graph_temp](https://github.com/nayanbarhate/Surfs_up/blob/main/Resources/June_graph_temp.png)

![Dec_graph_temp](https://github.com/nayanbarhate/Surfs_up/blob/main/Resources/Dec_graph_temp.png)

## Summary:
The investor's main concern was getting rained out too frequently.  Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close.  The temperature data is not strongly skewed for either month.  The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation.  The data supports opening a Surf and Ice Cream shop year-round.



