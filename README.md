# Jobathon-Apr-2022-AV
participated and scored 101 in  jobathon april Analytics Vidhya

<h1>Problem Statement</h1>
ABC is a car rental company based out of Bangalore. It rents cars for both in and out stations at affordable prices. The users can rent different types of cars like Sedans, Hatchbacks, SUVs and MUVs, Minivans and so on.

In recent times, the demand for cars is on the rise. As a result, the company would like to tackle the problem of supply and demand. The ultimate goal of the company is to strike the balance between the supply and demand inorder to meet the user expectations. The company has collected the details of each rental. Based on the past data, the company would like to forecast the demand of car rentals on an hourly basis.

<h1>Objective</h1>
The main objective of the problem is to develop the machine learning approach to forecast the demand of car rentals on an hourly basis.

<h2>Approach</h2>

<ul>i performed basic eda to understand when the spike starts. added a holiday indicator to take into account all weekends and major indian festivals as those days would show more demands</ul>
<ul>used t test to find if all columns were relevant to demand or not </ul>
<ul>I used linear regression , decision tree regressor, knn but xgboost and catboost gave me the best results </ul>
<ul>used catboost with optuna to study hyperparameters </ul>
<ul>removed year column </ul>
<ul>lastly xgboostregressor with max depth of 8 gave me best prediction.</ul>
