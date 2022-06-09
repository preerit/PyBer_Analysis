# PyBer_Analysis
## Overview of the analysis
* Pyber, a ride-sharing app company valued at $2.3 billion, wants to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO / decision makers. 
* Python is used for this analysis. Matplotlib package is used for visualization
* This task requires to look into two data sets, 'city data' which has the information on city category (urban/rural/suburban) and driver count per city and 'ride data' which has the information on rides per day and fare per ride. The 2 data sets have to be merged to successfully analyse the information 
* Different types of powerful visualizations like bubble chart (that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural), box and. whisker plots (to show the number of rides for each city type, the fares for each city type, the number of drivers for each city type) and pie chart (for % total fares, % total rides and % total drivers per city) are created
* A summary DataFrame of the ride-sharing data by city type is created. Following this, a multiple-line graph that shows the total weekly fares for each city type is created.

---

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

![PyBer_fare_summary](https://github.com/preerit/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

<img width="636" alt="Screen Shot 2022-06-09 at 3 42 14 PM" src="https://user-images.githubusercontent.com/105027698/172950248-8a3ae92a-759d-4602-9e17-83de5f0694a8.png">

### City Type:urban
* Has the highest number of rides
* Has the highest number of drivers
* Least average fare per ride and average fare per driver

### City Type:rural
* Has the least number of rides
* Has the least number of drivers
* Highest average fare per ride and average fare per driver

### City Type:suburban
* Lies in between urban and rural cross-sections

The data also shows more fluctutations in total fares in urban over rural and suburban city types.

