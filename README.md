# Ford GoBike System Data Exploration
## by Thomas Tran


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 
The dataset (https://www.fordgobike.com/system-data) consisted of 17 variables such as duration, gender, ages, time and etc. In this project, I will focus on the record of individual trips taken in from 2017 to February, 2019. 

Due to member ages more than 60 years old are small and ages from 18 to 60 takes most of the users (95%). With this outliers can make the statistics go wrong. So I tidy the data with popular ages only. I generated new variables such as time of users taken trip, age groups, distance estimates, etc. in order to check-out easily and analyze the dataframe. For best prediction later and have the specific analyses, I decided to focus on San Fancisco area by limiting with latitude and longitude.

## Summary of Findings

The most common duration is around 450-500 seconds, but due to some outliers (over 3000 seconds) the average duration raised to 792 seconds. There is an amazing thing that the early results show that average durations of Customers are higher than Subcribers. But later, charts showed the number of Customers are less than Subcribers. This can conclude the quality of Subcribers Trips are not good as Customers. Besides, most of users are younger (from 25-40 years-old), they have longer trips than others and most of Customer are younger than most of Subcribers.

Interestingly, it appears that although number of customers is less than number of subcribers but the trip durations and distances of Customers are higher than Subcribers. That proves Customers are really interested and serious in this kind of sports.

Finally, duration of Females and Customer type are higher than Males and Subcribers. People usually take bike trip in the morning and in the evening and on weekdays. And Customers will take trip with higher quality (higher duration, higher distance) especially at ages range from 25 to 40 years old.

## Key Insights for Presentation

For the presentation, I focus on the influence of time, genders and type of users data. I start by introducing the time distrubition in days and weeks followed by duration distribution, then plot the duration, timeframe in a day with distance data. I tried to use different kind of plots and color palettes for each variables to make sure it is clear and to ber interested that they're different between each other.
