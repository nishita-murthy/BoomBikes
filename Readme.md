## **Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

## **Business Goal**

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## **Conclusion**
We have a R-squared value of 83.6% on train data and 80.4% on test data. Based on the above table, we can understand that temperature is the highest significant variables and decreases as you move down the table.

Equation of best fit line can be calculated by using the standard formla:

cnt = const + feature1 x co-efficient1 + feature2 x co-efficient + .......... + feature'n' x co-efficient'n'

All of the positive coefficients, such as temp,season Summer, suggest that when these values rise, so will the value of cnt.
All of the negative coefficients indicate that increasing these values will cause the value of cnt to decrease.

- With the biggest coefficient, temperature is the most significant.
- Followed by weathersit Light Snow.
- Bike rentals are more significant in September.
- During the holidays, rental rates are lower.


