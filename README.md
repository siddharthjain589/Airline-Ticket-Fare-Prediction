# End to End Machine Learning Project: Implemented Data Science Life Cycle
Predict Fare of Airlines Tickets using Machine Learning 

It shows and explains the full real-world Data. Starting with 
importing messy data , cleaning data, merging and concatenating data, grouping and aggregating data, Exploratory Data Analysis through to preparing and processing data for Machine Learning Model.

Following data science life cycle steps I implemented in this project-
1. Data Collection
2. Data Cleaning
   - Deal with missing values
   - Converted feature data types into appropriate data types for ML model training
   - clean some features and Derived other features from it
3. Preprocessing of some features
4. Data Analysis
    - such as when most of the flights take off
    - on which route jet airways extremely used
    - find the relationship & correlation between features and target variable (label)
    - Airline vs Price Analysis
5. Feature Engineering
    - applied one-hot coding on data (implemented from scratch)
    - due to curse of dimensions problem implemented target guided encoding also
    - implemented label encoding from scratch
    - drop unneccessy columns
    - Detect the outlier using box plot, histogram
    - replace the outlier with median value
6. Feature Selection
    - used the mutual information for feature selection
7. Model Building
    - Used Random forest regressor
    - evaluate the model using MEA, MPAE, MSE, RMSE, R2 score
8. Dumping the model
    - Dump the model in file in local system using pickle
9. Automate the Machine Learning Pipeline
    - Implemented function of model training, testing and for evaluating
    - call this function through various models
    - compared the result and accuray of each model to find which one is best model
10. Hyper Tune Machine Learning model
     - Use the Randomized Search CV to find out the best optimized model with best parameter
     - to get best result 



