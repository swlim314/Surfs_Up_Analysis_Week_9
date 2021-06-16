# Analysis of Weather Differences
## Overview of Weather Data analyzed
I was tasked to determine if there were signifcant weather differences between the months of June and December. My client is looking
at opening a business that deals with both surfing and ice cream, and wants to see if it is sustainable year round. Previously I had been
tasked with organizing the weather data. After querying the temperatures in June and December, I then ran summary statistics on the two months.
## Results of the Analysis
- The first major difference between the two data sets was that the mean temperature in June was ~3 degrees fahrenheit warmer than in
December, at 74.94 vs December being at 71.04. This difference in temperature is relatively mild.
- Another difference between the two months is that while the maximum temperatures are relatively the same, 84 in June and 83 in December,
the difference in the minimum temperature is much wider, with it being 64 in June and 56 in December. There is a potential for December to
be a less active month in terms of ice cream sales.
- One final difference between the two months is the count of data that was returned. Looking at the two tables below, June returned 1700
data points whereas December only returned 1517 data points. This could potentially affect how accurate the summary statistics, although
based off the currently existing std (June at 3.25, December at 3.75), most of the data falls within the same range.

These differences are based off the following two summary statistics tables: 

**June Temperature Statistics**

![June Temperature](https://github.com/swlim314/Surfs_Up_Analysis_Week_9/blob/4d9088e218b4b419d948a6ac265e9e5e9174567d/Resources/June%20Temperatures.png)

**December Temperature Statistics**

![December Temperature](https://github.com/swlim314/Surfs_Up_Analysis_Week_9/blob/4d9088e218b4b419d948a6ac265e9e5e9174567d/Resources/December%20Temperatures.png)

## Summary
Based on the results of the summary statistics, although there is a slight difference in the average temperatures, it seems like both June
and December are relatively similar in terms of feasability for a Surfing/Ice Cream business. Two additional queries that would benefit 
this analysis are one that determines the amount of rainfall or precipitation throughout the year, which would impact both sales, as well 
as a query to determine the high/low tides in the area which would impact the feasability of the surfing portion of the business.
