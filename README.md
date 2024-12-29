Regression problem Objectives :

Make accurate estimates of house rental prices that are useful for both tenants and landlords.
Gain insights into market trends and patterns to identify factors that influence house rental prices.
Provide valuable information to support decision-making processes for tenants and landlords.
Help overcome the information asymmetry between tenants and landlords to facilitate fair and informed rental transactions.

To know the trend of house rents in a certain location.
This project aims to analyse various parameters like number of bedrooms & bathrooms, size of the house, area, furnishing status, etc. and predict the house price accordingly. 
This application will help to provide a better and fast way of performing operations. 
To provide proper and fair house rent to the customers. 
To eliminate need of real estate agent to gain information regarding house rents. 
To provide best price to user without getting cheated. 
To enable user to search home as per the budget.




The optimization techniques used for improvising the accuracy :

Feature Engineering
Columns named ‘Point of Contact'(-0.48),'Posted On','Area Locality'(0.026) shows poor correlation with target variable.
Data Preprocessing
Transformed object type ‘Floor’ column into int type and encoded it into numerical values.
Hyperparameter Tuning
GridSearch for hyperparameters like ‘learning-rate’, ‘n-estimators’ and ‘max-depth’.
Cross-validation
GridSearchcv with k-folds=4
