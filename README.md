# Bike Sharing Assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info] (#general-information)
* [Technologies Used] (#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
### Project Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is facing very difficult situation to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all-around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know: 
	* Which variables are significant in predicting the demand for shared bikes.
	* How well those variables describe the bike demands

### Business Objective
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Data set
The dataset used here is the csv file having bike sharing dataset.


## Conclusions
* The R2 score on the train and test is 0.84 and 0.81.
* The 3 variables to be considered for demand in bikes are temp, yr_2019, weathersit_snow
* Bike usage is higher in summer and fall seasons.
* Bike usage is particularly high when the weather is clear.


## Technologies Used
* NumPy - version 1.26.4
* Pandas - version 2.1.4
* matplotlib - version 3.9.1
* seaborn - version 0.13.2
* sklearn - version 1.2.2
* statsmodel - version 0.14.0
 


## Acknowledgements
- This project was inspired by UpGrad IIITB programme.


## Contact
Created by [@sravanthichundi]


