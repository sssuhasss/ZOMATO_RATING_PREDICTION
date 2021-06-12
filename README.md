# ZOMATO_RATING_PREDICTION

## DATA SOURCE
 https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants
 
## DATA Preprocessing
  1) Consider only the following Features/Columns for Consideration 
              [online_order	]  [book_table]  	[ratings] 	[votes] 	[avg_cost] 	[dish_liked]	[cusines]
  2) Apply Label Encoding to [book table] and [online order] columns
  3) Count the number of Cusines to get new column [cusine count] and apply label encoding
  4) Count the number of dishes liked from [dish liked] to get new column [disk count] and apply label encoding
  5) Apply Min Max scaler
  6) Remove Null Values
 
## Models
  1)Here the above data is split into Training Data and Test Data and Fed into different Models 
  2)Grid Search CV is used to find the best parameters for certain Models
  3)The Regression Model Metrics used to measure performance is Mean Absolute Error
  4)The Performance of all the Models are summarised below
  
## Performance Summary

