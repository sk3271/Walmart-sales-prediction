Walmart-sales-prediction

![Screenshot 2023-10-14 141439](https://github.com/sk3271/Walmart-sales-prediction/assets/117064680/e31d209a-836d-4a44-8bb1-26f7fc6ac8db)


[https://github.com/Pradnya1208/Walmart-store-sales-prediction](https://github.com/sk3271/Walmart-sales-prediction/blob/main/Walmart_sales_forecasting.ipynb)#objectives

Data from Walmart stores accross the US is given, and it is up to us to forecast their weekly sales. The data is already split into a training and a test set, and we want to fit a model to the training data that is able to forecast those weeks sales as accurately as possible. In fact, our metric of interest will be the weight Mean Absolute Error.

[https://github.com/Pradnya1208/Walmart-store-sales-prediction](https://github.com/sk3271/Walmart-sales-prediction/blob/main/Walmart_sales_forecasting.ipynb)#dataset
https://www.kaggle.com/avelinocaio/walmart-store-sales-forecasting/data

This is the historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

stores.csv: This file contains anonymized information about the 45 stores, indicating the type and size of store.

train.csv:

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - the store number
Dept - the department number
Date - the week
Weekly_Sales - sales for the given department in the given store
IsHoliday - whether the week is a special holiday week
test.csv:

This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

features.csv:

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number
Date - the week
Temperature - average temperature in the region
Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
CPI - the consumer price index
Unemployment - the unemployment rate
IsHoliday - whether the week is a special holiday week

https://github.com/Pradnya1208/Walmart-store-sales-prediction#implementation
Libraries: sklearn Matplotlib pandas seaborn NumPy

#Feedback
If you have any feedback, please reach out at shankarsolanki7891@gmail.com

















