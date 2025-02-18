# Uber_and_Lyft_Project

## Project Goals

This project aims to analyze and compare ride-hailing services, focusing on Uber and Lyft in Boston to understand pricing dynamics, availability, and demand patterns. This project also completed by predictive model to estimate ride prices based on multiple influencing factors.

## Project Contents

1. Availability and Demand Analysis: Identify which services are more used and available in different locations

2. Temporal Analysis: Identify the busiest hours for ride requests, and analyze how ride prices fluctuate during rush hours and off-peak periods

3. Price and Demand Analysis: Identify price distribution, and compare average ride prices between Uber and Lyft to identify cost differences based on destination, hours, cab, and service types 

4. Weather and Price Correlation: Analyze the correlation between weather factors and price

5. Price Prediction Model: Build a regression model to predict ride prices based on several factors

## Project Conclusions

From the data, we can conclude that Uber has a higher user base than Lyft, with a notable difference of 23 thousand users. Both Uber and Lyft have 6 service types and show an equal distribution across their service types.

The top pickup and destination location for Uber and Lyft is the Financial District which is the business heart of NYC. It's home to hundreds of offices and the headquarters of many major financial institutions. The remaining top locations differ, highlighting distinct user preferences for each service.

Trip patterns for both Uber and Lyft show similar trends. Uber consistently has slightly more trips than Lyft throughout the day. The highest number of trips occurs around midnight (11 PM to 0 AM) possibly due to the night activities, and the lowest number of trips occurs around early morning (6-7 AM) possibly because of fewer commuters. Both services experience a surge in trips during rush hours around 8 AM, with stable volumes of rides in the afternoon. 

The price distribution for both services is right-skewed, indicating more affordable rides but at some point, there are few expensive rides due to rush hours, distance, and other factors.
Boston University stands out as the most expensive destination while Haymarket Square is the cheapest. The price of Uber and Lyft services varies with Lyft being slightly more expensive on average. Moreover, the correlation between weather and pricing is weak, indicating other factors drive pricing more significantly.

In terms of model performance, the prediction model has a R2 value of 93%, indicating that it is relatively accurate for predictions. This is also supported by relatively low MAE and MSE, which indicate that the model's predictions are generally close to the actual values.
