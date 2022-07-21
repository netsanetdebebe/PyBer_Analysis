# PyBer_Analysis
PyBer Analysis Visualization

Overall objective of this analysis 
The overall objective of this assignment was analyzing and creating a summary DataFrame of the ride-sharing data for PyBer and creating a visualization of graph data using the Matplotlib library. The analysis required the application of Pandas and Python skills. 

Specific objectives 
Two specific tasks were executed in the analysis. The first was getting the total number of rides, total number of drivers, and the total fares for each city type through the Pandas groupby() function with the count() and sum() methods on the PyBer DataFrame columns. Average fare per ride and average fare per driver for each city type were also calculated and added to a new DataFrame. 

Specifics of the first part of the analysis required the use of the groupby() function to create a series of data that has the type of city as the index and apply the count() method to the ride_id column. Then, using the same function, a series of data that has the type of city as the index was created and the sum() method was applied to the driver_count column. Then, the groupby() function was used to create a series of data that has the type of city as the index and the sum() method was applied to the fare column. Then, averages for fare per ride and fare per driver were calculated by dividing the sum of all the fares by the total rides, and total drivers respectively. 

In the second part of the analysis, a multiple-line graph that shows the total fares for each week by city type was created. Specifics of the second part of the analysis required the use of two Pandas functions: pivot() and resample(). The pivot() function was used to convert the DataFrame created in previous steps so that now “date” is the index; each column is a city "type,"; and, the values are the "fare." Then a new DataFrame was created using the loc method on a date range of 01-01-2019- through 04-28-2019. Then the resample() function was applied to create a new DataFrame the sum() method was applied to get the total fares for each week. Then, a graph of the resampled DataFrame was created using the object-oriented interface and the df.plot() methods and  the "fivethirtyeight" graph style in Matplotlib. A .png file showing a line graph was then generated.  

The third component of the assignment was generating a written report of the analysis process and the results as a README file. 

Executed/methods 
The analysis required the application of Pandas and Python skills using Jupyter Notebook. Different functions and methods in Pandas such as groupby() function, the count(), and sum() methods, pivot(), and resample() were applied. 

Results	
-	There are more rides in urban areas compared to suburban and rural areas 
-	Compared to suburban and rural cities, urban areas have a higher fare for all months 
-	There are more drivers in urban areas than suburban and rural areas 
-	January appears to be a month for lower fares in all city types 
-	Driver count, city type, and fares appear to be correlated 
-	Fares appear to go up in all city types by the end of February 
-	The end of February shows an uptick in fares 
-	The beginning of January shows low fares for all city types 
-	It appears that there is much fluctuation in fare average ranges in rural cities compared to urban areas  
-	The chart shows a relatively similar pattern of fare increase and decrease for all city types throughout the months. It does not appear that there is  

Summary 
There are more drivers and more rides in urban areas, followed by suburban and rural areas. Fares for rides are also higher in urban areas compared to suburban and rural areas. This could be due to demand. 

All counts, averages, and ranges for the city types are within the logical assumption of a ride service, such as what Pyber provides, that banks on population size. There is no much of an anomaly or inconsistency between the city types. However, the CEO can consider variable fare system in the different city types for different seasons/months. Varied consumption behaviors in the different city types could be one variable affecting fares. For example, around the end of March, fares go up in rural cities while the same period shows a decline in urban areas.  

The beginning of January appears to be a period of relatively low fares, may be because of decline in demand that follows a spree of spending for a series of holidays in the previous few weeks. CEO can devise strategies to encourage more drivers to be on the road and offer promotions to riders by lowering costs as much as possible. 

Some urban areas do have small number of drivers compared to other urban areas. For example, Lake Jonathanshire, an urban area does have lower number of drivers than the rural city Michaelberg. The fares in Lake Jonathanshire are also lower compared to other urban areas. This could mean that fares are This could be an outlier, but it is possible that the expectation of having more drivers in urban areas than rural areas might not be always correct. However, in the PyBer date, there appears to be a consistent number of drivers in most urban cities. 

Because of the higher number of drivers in urban areas, the average fare per driver and the average fare per ride in urban areas is lower than in suburban and rural areas. This is despite the higher fares in urban areas. Considering the very high number of drivers in urban areas, the averages are normal. The CEO could consider incentivizing drivers in urban areas for better driver income and better attrition.     





