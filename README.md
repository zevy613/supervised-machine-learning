# Supervised-Machine-Learning

## Using Decision Trees and Linear Regression models to predict Item Outlet Sales.

Author: William Borenstein

### Business problem: 
Using a data set that contains columns like, weight, fat content and visibility and outlet types such as outlet size and outlet location I will attempt to predict the Item Out Sales price.

### Goal: 
Predict the Outlet Sales

### Data
This data set has 12 columns or features and 8,523 rows or entries. 
The target column is 'Item_Outlet_Sales'

## Methods 
First we understand the data by checking the number of missing values, the number of duplicate rows and if we have any inconsistencies in our data.

Second, we train/test split our data to prevent any data leakage.

Third, we will impute, scale, and one-hot-encode all of our data. We accomplish this using column transformers and pipelines.

Fourth, we apply two regression models; a) Linear Regression and b) Decision Tree Regression.

## Results
Visual #1

<img width="416" alt="image" src="https://user-images.githubusercontent.com/54513705/187002776-9185d9bb-f835-4f4c-b66d-acce97929106.png">

From Visual #1 we can see that Grocery Stores have the least Outlet Sales and that Supermarket Type 3 has the most.


Visual #2

<img width="374" alt="image" src="https://user-images.githubusercontent.com/54513705/187002988-1e1758bb-32dc-43bc-b0db-a4e38358e648.png">

We can see from Visual #2 that starchy foods have the highest outlet sales.

## Model 
The Desicion model that I used was a Decision Tree Regression. I chose this becuase it resulted in the highest R-Squared score. The MSRE shows that my model is precise up to 1,055 dollars. 

Metrics for testing data
R^2 :  0.596
RMSE :  1055.685

## Recomondations:
The reason I chose this model is because it works best with the data that was given. The score on the testing data was higher then the other models that were used.

## Limitations & Next Steps
One way I could enhance this model would be to add more hyperparameter tuning on more variables.
Also, if some columns were eliminated that could produce a better model as well.


## For further information 
zevy613@gmail.com
