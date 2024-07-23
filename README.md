# House Rent Prediction

## Project Overview
The House Rent Prediction project developed a robust machine learning model to accurately predict house rents based on various features. This model helps in understanding the key factors influencing rent prices, useful for property owners and potential tenants.

## Objectives
- Analyze the dataset to identify key features affecting house rent.
- Preprocess the data for machine learning models.
- Train and evaluate multiple supervised machine learning algorithms.
- Select the best-performing model for rent prediction.

## Data Collection
The dataset, sourced from [mention source], includes features such as:
- Number of balconies
- Facing direction
- Floor number
- Furnishing description
- Lift availability
- Maintenance amount
- Property age
- Property size
- Rent amount

## Data Preprocessing
1. **Data Cleaning:** Removed null values and handled missing data. Dropped irrelevant columns such as 'locality', 'localityId', and 'parking'.
2. **Feature Engineering:** Created new features like price per square foot. Converted categorical variables (e.g., facing direction, furnishing description) into numerical values using one-hot encoding.
3. **Data Normalization:** Scaled features to ensure uniformity using methods like Min-Max scaling or Standardization.

## Model Selection and Training
Several supervised machine learning algorithms were trained and evaluated, including:
- **Linear Regression**
- **Decision Trees**
- **Random Forest**
- **Gradient Boosting Machines (GBM)**
- **Support Vector Machine (SVM)**
- **Neural Networks**

## Model Evaluation
Performance of each model was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Cross-validation ensured the model's robustness and prevented overfitting. The Random Forest model demonstrated the best performance with the lowest loss function values, providing the most accurate predictions.

## Results
- The Random Forest model provided the most accurate predictions with the lowest MAE and RMSE.
- This model effectively captured complex relationships between features and rent prices.

## Conclusion
The House Rent Prediction project successfully developed a machine learning model to predict house rent prices. This project highlights effective data preprocessing, feature engineering, and the application of advanced supervised ML algorithms to solve real-world problems.
