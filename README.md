# House Price Prediction Using Linear Regression

This project predicts house prices using Linear Regression with two models:  
1. Model 1: Trained on square footage, number of bedrooms, bathrooms, and other features highly correlated with house prices.  
2. Model 2: Trained only on square footage, number of bedrooms, and bathrooms.  

### Dataset(#test.csv,#train.csv)
The dataset contains 1,460 samples and 81 features, with the target variable `SalePrice`. Key features include `GrLivArea` (living area), `BedroomAbvGr`, and a derived feature `TotalBathrooms`.  

### Results  
- Model 1 achieves a Mean Absolute Error (MAE) of ~22,000.  
- Model 2 has an MAE of ~33000.  

### Setup  
- Run the notebook using jupyter notebbook.  

### Conclusion  
Model 1, leveraging more features, performs better, while Model 2 offers a simpler alternative. Both provide insights into house price prediction.  
