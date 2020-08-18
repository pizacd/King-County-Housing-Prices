# **Predicting Seattle Housing Prices**

[LinkedIn](https://www.linkedin.com/in/douglas-pizac-ms/)
[Kaggle](https://www.kaggle.com/pizacd)

Found a dataset on housing prices in King County, WA on [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction).

## Cleaning the data

No null values to fill, but if a house has never been renovated, the renovation year is designated as 0. 

## Built and Deployed Linear Regression 

Using scikit-learn, I divided the data into test and training sets with the goal of predicting housing prices. Besides using the features provided with the data, I also created an additional feature examining the years between the pricing date and the build date. My linear regression model explained 70% of the variance in predicting King County housing prices.