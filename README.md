# Mid_camp_project
[tableau](https://public.tableau.com/app/profile/nancy5857/viz/project_16795827804480/Story1?publish=yes)
[data](https://www.kaggle.com/datasets/shilongzhuang/-women-clothing-ecommerce-sales-data)


# Women’s clothing project 
**Nancy Omozokpea**  
**IronHack, Duisburg 25 Mar 2023**

## Overview

* What can we do to maximize the revenue?  

Used:

	* Python
	* Statistical analysis
	* Data visualization
	* Jupyter Notebook
	* Tableau
	* Machine Learning (Logistic Regression)
  
  ## Data Preparation

### Overview: 
* Data is about womens clothing.
	* [dataset](https://www.kaggle.com/datasets/shilongzhuang/-women-clothing-ecommerce-sales-data)
  
* 8 columns 
* 527 rows 
* columns:
* 
 Initial Column: 

order_id, order_date, sku, color, size,	unit_price, quantity, revenue

 Comment:
 order_id & sku were removed because  the columns were not needed

New Column:
order_date, color, size, unit_price, quantity, revenue,	day, month, year

Comment:
Day, month & year were added to understand the revenue and the costumer behavior

### Data Wrangling and Cleaning
  
- Overall Data description
- Deleting  columns with hight unique values: User,Merchant Name 
- Looking for outliers column by column 
- Dealing with Nan Values for each column
- Creating plots for each column to check the correlation to revenue 
- Checking for correlation with target feature


### Data Storage

* Dump your data as `.csv` file. 

## Data Analysis
* Use [tableau](https://public.tableau.com/app/profile/nancy5857/viz/project_16795827804480/Story1?publish=yes) to analyze 


### Data Exploration and Visualization
Used Tableau to visualize my overall data.

### Model Training and Evaluation
- Define predictors and target values (X, y)
- Standard scaling for numericals : for Train and Test set
- OneHotEncoding for categoricals : for Train and Test set
- Balancing data : Oversampling our target values in our Train set. 
- Models : LogisticRegression 
- Compared accuracy 


## Conclusion

-Initially revenue was used as the target, this was changed to quantity, because the result was more meaningful. 
- Our model had an accuracy of 65%.

- Due to small available dataset, modeling could not produce reliable prediction.  Analysis would be the best method here. 
