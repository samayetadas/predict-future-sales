# predict-future-sales
# This is Based on the Kaggle Competition 'Predict Future Sales'
The data given is a time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company.We have to predict total sales for every product and store in the next month.Note that the list of shops and products slightly changes every month.
# Rank Achieved:2359 out of 9305 participants

# File descriptions
* sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.
* test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.
* sample_submission.csv - a sample submission file in the correct format.
* items.csv - supplemental information about the items/products.
* item_categories.csv  - supplemental information about the items categories.
* shops.csv- supplemental information about the shops.
Unfortunately ,the sales_train.csv has not been included in the repository because of its large size.Please download the dataset from the Kaggle page https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data


# Data fields
* ID - an Id that represents a (Shop, Item) tuple within the test set
* shop_id - unique identifier of a shop
* item_id - unique identifier of a product
* item_category_id - unique identifier of item category
* item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
* item_price - current price of an item
* date - date in format dd/mm/yyyy
* date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
* item_name - name of item
* shop_name - name of shop
* item_category_name - name of item category
