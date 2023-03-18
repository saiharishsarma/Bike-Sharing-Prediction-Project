# Bike-Sharing-Prediction-Project

Seoul is the official capital city of South Korea. 
Seoul Metropolitan Government provides rental bike service to public. 
These bikes are deisgned to be used by all women, the elderly and the infirm. 
These bikes are made light weight and durable.

![image](https://user-images.githubusercontent.com/99181593/226119137-0f2dd976-0799-4fee-a6f9-077b12a9d6cb.png)


--Project Summary:

--Data Description:

Date - Date

Hour - Hour of the day (0-23)

Temperature - Temperature of the day

Humidity - Humidity measure

Windspeed - Windspeed

Visibility - Visibility measure

Dew Point Temperature - Dew point Temperature measure

Solar Radiation - Solar Radiation

Rainfall - Rainfall in mm

Snowfall - Snowfall measure

Seasons - 1 = Spring, 2 = Summer, 3= fall, 4 = winter

Holiday - Whether a holiday or not

Functional Day - Whether a functional day or not


--Problem Statement:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. 
It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. 
Eventually, providing the city with a stable supply of rental bikes becomes a major concern. 
The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


--Project Flow:

1.Data Cleaning & EDA
2.Feature Engineering
3.Pre Processing Data
4.Target Conditioning
5.Modelling, Evaluation & Tuning
6.Model Explainability

Conclusion:

EDA Outcomes:

1.The use of bikes is high in between the months of MAY and OCTOBER.

2.The bikes are using while reaching and leaving office hours.

3.he count of rental bikes is high in summer, Demand is very low in Winter.

4.The use of bikes is high, when the temperature ranges between 25 and 30 degrees.


Data Quality Issues:

1.Outliers available, they are removed.

2.Multicollinearity

3.Correlation

4.Feature Encoding

Model Outcomes:

1.Among all models, Random Forest and Gradient Boosting are worked better.

2.Temperature, Humidity, Hour and Functionalday are the most influencing features on Count of Rental Bikes.

3.Linear, Lasso and Ridge Models giving poor results as they are giving r2_score of 0.622, where as the Random forest and Gradient Boosting models giving as 0.858 and 0.873 respectively.

4.Ensemble Modeling is preferred as the Mean Squared Error is drastically decreased with Random Forest and Gradient Boosting Regressor.


---------Dataset: Provided by Almabetter.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
If you find any mistakes and for any suggestions, kindly reach out me through mail.
mail_id: saiharish.swarna@gmail.com

-----Thankyou for reading-----




