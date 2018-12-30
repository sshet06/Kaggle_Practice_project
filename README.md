## House Prices: Linear Regression Techniques
This Project focuses on most famous **Ames Housing dataset**.Linear Regression with 2 Regularization methods viz L1 and L2 is applied to predict the housing price.
Following are the steps taken for Data Preprocessing:
* Outlier Removal
* Log Tranform the target variable(SalePrice) to reduce the skewness
* Feature Engineering : Filling in missing data , Correlation with target variable
 #### Modelling ####
* Linear Regression without regularization :Validation Error:0.13131393379532302
* Linear Regression with L1 regularization :Validation Error:0.11124985346543763
* Linear Regression with L2 regularization :Validation Error:0.11251439629640089

**Conclusion:** L1(Lasso) preforms better as it eliminates most of the features which have no significance contribution in evaluating SalesPrice.

#### How To Run the code: #### 
Following Python Libraries are required to be installed prior to running the code
* Numpy
* Pandas
* MatplotLib
* Scikit Learn
* Seaborn

Alternatively run the following command: **pip instal -r requirements.txt**

