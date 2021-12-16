# Predicting the Apple inc. Stock Closing Price 
##### Nourah Alsaadan

## Abstract 
#### The goal of this project is to predict Apple inc. stocks closing price, by using regression models, and for that Apple stocks dataset provided by Yahoo finance will be used. 

## Design 
#### The data provided by Yahoo finance, and it's Almost clean and ready to use, I checked the missing values, dublicats and noisy data, after that I've created some visualisation, and lastly applied the models.

## Data
#### The AAPL dataset which was used in this case study has been taken from Yahoo Finance, it has 7 columns and 8050 Rows:

Variable  | Description 
------------- | -------------
Date  | Date
Open  | Opening Price
High  | Highest price 
Low  | Lowest price
Close  | Closing price
Adj Close  | The adjusted closing price
Volume  | Number of shares

## Algorithm 
#### To solve this problem, I used 3 Algorithem to see which one will give the best results, and right before I've created a new column and call it prediction and give it a value from 'x' days from the future (taken from the Close column) and then used these models and compare them with the orig one. 

Algorithm  |  Results 
------------- | -------------
Liner Regression  | ![This is an image](https://github.com/nourahsaud/T5-Data-Science-Bootcamp/tree/main/Assets/LR.png)
Decision Tree  | ![This is an image](https://github.com/nourahsaud/T5-Data-Science-Bootcamp/tree/main/Assets/DT.png)
Random Forest  | ![This is an image](https://github.com/nourahsaud/T5-Data-Science-Bootcamp/tree/main/Assets/RF.png)

The Results above shows that the Decisions Tree gave the best results.

## Tools
#### The tools used to solve this problem:
- Numpy
- Pandas
- Matplotlip 
- Seaborn
- DecisionTreeRegressor
- RandomForestRegressor
- LinearRegression

## Communication 
- A comparison between the Closing price and the other numaric values
![This is an image](https://github.com/nourahsaud/T5-Data-Science-Bootcamp/tree/main/Assets/Comp.png)
- The Closing Price 
![This is an image](https://github.com/nourahsaud/T5-Data-Science-Bootcamp/tree/main/Assets/Close.png)

