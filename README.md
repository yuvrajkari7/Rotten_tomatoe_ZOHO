# Rotten_tomatoe_ZOHO-Project Overview 

* Build a high performing classification algorithm to predict whether a particular movie on Rotten Tomatoes is labeled as 'Rotten', 'Fresh', or 'Certified-Fresh'.


## Code and Resources Used 
**Python Version:** 3.11  
**Packages:** pandas, numpy, scipy, sklearn, matplotlib, seaborn, xgboost

## Dataset Used 
**Given dataset from ZOHO:** (https://github.com/yuvrajkari7/Rotten_tomatoe_ZOHO/blob/main/Rotten_Tomatoes_Movies3.xls.zip)

## Data Cleaning
I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

*	Removed columns with high number of null values.
*	Removed rows with null values.
*	Checked for no duplication.
*	Made columns for the number of directors in each movie.
*	Made columns for the number of authors in each movie.
*	Made columns for the number of actors in each movie.

## EDA
* I looked at the distributions of the data.
* Correlation with the target value.
* The value counts for the various categorical variables.
* I removed Outliers.



## Model Building 

* First, I transformed the categorical variables into dummy variables.
* I scaled the data using StandardScaler()
* I also split the data into train and tests sets with a test size of 20%.   
   

**I tried three different models:**
* Decision Tree Model
* Random Forest Model
* XGBoost Model 
