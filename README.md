## New York City Taxi Trip Duration Prediction

The purpose of this analysis is to accurately predict the duration of taxi trips in New York City. This work is for a [Kaggle competition](https://www.kaggle.com/c/nyc-taxi-trip-duration). 

## How the problem is solved:
*  Developed a Machine Learning model to predict the trip duration of the rides using Linear Regression and Random Forest.
*  Eliminated the outliers, preprocessed the dataset and performed feature engineering and feature selection to improve our model.
*  Performed EDA to get some valuable insights, calculated the trip distance from longitude and latitude using Havershine Algorithm and Clustered the prime locations using Folium library of Python
* Evaluated and trained all the models using 10 K-Fold cross validation and discovered Random Forest performs better with ~80% accuracy.
