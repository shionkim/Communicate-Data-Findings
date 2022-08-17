# Ford GoBike System Data
## by Shion Kim


## Dataset

The data consists of information regarding bike travels, including
duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, and bike_share_for_all_trip

Link: https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Summary of Findings

In this data investigation, I expect duration sec, start time, end time, and user type to play a significant role. In this dataset, there could be a relationship between three genders. I believe that the user's age and latitude will also play a significant effect. As I predicted, duration has a long-tailed distribution, with a large number of users on the low end and a small number on the high end. The duration distribution appears right-skewed when shown on a log-scale, with one peak between 350 and 390. Surprisingly, following the year 2000, there is a significant drop in frequency.

The length of the ride was interestingly correlated with the year of birth. When the duration was plotted, an essentially exponential connection was discovered. Box plots show that there aren't many variances depending on the user's gender and the day of the week. There was also a fascinating link between start time and end time, which was called start station longitude. On the other hand, there is a strong negative association between start station longitude and start station latitude, end station longitude and start station latitude, and end station longitude and end station latitude, as well as end station longitude and end station latitude.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the duration of trips
and start time. I start by introducing the  variable, followed by the pattern in carat distribution, then plot the
transformed scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the box plots of gender and duration across day of the week. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
