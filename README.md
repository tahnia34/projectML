# Boston Housing Price Prediction

This project uses machine learning to predict the median house prices in Boston, Massachusetts, based on a set of 13 socioeconomic and structural features from the Boston Housing dataset. Using linear regression as the primary model, the goal is to accurately predict the target variable, medv (Median value of owner-occupied homes), while exploring various techniques to improve model accuracy.

## Project Workflow
### Data Preprocessing:
Handled feature scaling to standardize the dataset, and applied potential transformations to improve model performance.

### Model Training:
Built a linear regression model to predict house prices, experimenting with feature engineering and regularization techniques for optimal performance.

### Evaluation:
Assessed the model using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and 
𝑅
2
R 
2
  score to gauge prediction accuracy.

### Improvement Techniques:
Explored advanced methods such as polynomial features, regularization (Ridge and Lasso), and alternative regression models to enhance model accuracy and robustness.

### Success Rate:
The model achieved an R² score of 0.669, explaining 66.9% of the variance in house prices. Despite its simplicity, it serves as a strong baseline, and further improvements through feature engineering and regularization can enhance its predictive accuracy, as shown by the reduced MAE, MSE, and RMSE.
