# surfs_up

using SQLite, SQLAlchemy, and Flask to Analyze weather

### Overview of the analysis

Using Python, Pandas functions and methods, and SQLAlchemy, we’ll filter the date column of the Measurements table in the *hawaii.sqlite* database to retrieve all the temperatures for the month of June and December. we’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Results

to get the results we have to follow these steps

1. A query to retrieve the June and December temperatures from the date column of the Measurement table.
2. Convert temperatures to a list.
3. Add list of temperatures to a Pandas DataFrame.
4. Summary statistics for the June and December temperature DataFrame.

which we can see the results in these pictures

![This is an image](june_temp.png)


![This is an image](dec_temp.png)

> The mean temperature for June is 75°F which is higher than the mean temperature for December 71°F. Standard Devision in December is 3.74 and 3.25 in June which is showing that we have more spreading temprature in December than June. by comparing both results we realize that both June and December are good months to surf.


### Summary

to be more clear about the data and the results, we can add *Measurement.prcp* to our query which shows precipitation for June and December and by creating some matplotlip graphs it makes it much easier visually to see the differences between the months.