# Bike Sharing - Multiple Linear Regression
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems  allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
### Business Understanding
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands.

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Objectives
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## General Information
    Steps for Multiple Linear Regression :
        Data Reading & Understanding
        Data Visualisation
        Creating Dummy Variables
        Exploratory Data Analysis
        Rescaling Features
        Model Building
        Model Assumptions
        Model Prediction
        Model Evaluation
        Conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
As per our final Model, the top 3 predictor variables that influences the bike booking are:

- Temperature (temp) - A coefficient value of ‘0.5499’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.5499 units.
- Weather Situation 3 (weathersit_3) - A coefficient value of ‘-0.2871’ indicated that, w.r.t Weathersit1, a unit increase in Weathersit3 variable decreases the 
  bike hire numbers by 0.2871 units.
- Year (yr) - A coefficient value of ‘0.2331’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.2331 units.
  So, it's suggested to consider these variables of utmost importance while planning, to achive maximum Booking.

The next best features that can also be considered are:

- season_4: - A coefficient value of ‘0.1307’ indicated that w.r.t season_1, a unit increase in season_4 variable increases the bike hire numbers by 0.1307 units.
- windspeed: - A coefficient value of ‘-0.1552’ indicated that, a unit increase in windspeed variable decreases the bike hire numbers by -0.1552 units.

For your Information:

The details of weathersit_2 & weathersit_3
- weathersit_2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist.
- weathersit_3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds.

The details of season_2 & season_4
- season_2: Summer
- season_4: Winter

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
    pandas - 1.3.4
    numpy - 1.20.3
    matplotlib - 3.4.3
    seaborn - 0.11.2
    StatsModel - 0.11.0
    Scikit-learn - 1.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This assignment is for an online advance course.
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/
- https://learn.upgrad.com/


## Contact
Created by [@vkarkera] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
