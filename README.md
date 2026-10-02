# Car Price Prediction

## Project Overview
This project focuses on predicting the selling price of used cars using Machine Learning techniques. It uses vehicle-related features such as present price, car age, kilometers driven, fuel type, transmission and ownership details to estimate resale prices.

## Objectives
- Analyze used car data to identify patterns affecting selling prices.
- Perform data cleaning, exploratory data analysis and preprocessing.
- Build regression models to predict car selling prices.
- Evaluate and compare model performance using regression metrics.
- Identify important features influencing predictions.

## Dataset
The dataset contains 301 records of used cars with features including:
- `Car_Name`
- `Year`
- `Selling_Price`
- `Present_Price`
- `Driven_kms`
- `Fuel_Type`
- `Selling_type`
- `Transmission`
- `Owner`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook / Google Colab

## Project Workflow
1. Data Understanding
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Categorical Encoding
6. Train-Test Split
7. Feature Scaling
8. Model Building
9. Model Evaluation
10. Feature Importance
11. Model Saving

## Machine Learning Models
- Linear Regression
- Random Forest Regressor

## Model Evaluation

| Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 1.22 | 0.62 |
| MSE | 3.48 | 0.87 |
| RMSE | 1.87 | 0.93 |
| R² Score | 0.85 | 0.96 |

The Random Forest model achieved a higher R² score and lower errors than Linear Regression on the test split used in this project.

## Key Findings
- Present price was the most influential feature in the Random Forest model.
- Car age and kilometers driven also contributed to price predictions.
- Random Forest captured patterns in the dataset more effectively than Linear Regression on the test set.
- Some prediction errors remained, particularly for certain higher-priced cars.

## Project Structure
```text
CodeAlpha_Car_Price_Prediction/
├── data/
├── notebook/
├── models/
│   ├── random_forest_model.pkl
│   └── standard_scaler.pkl
├── README.md
├── requirements.txt
└── .gitignore
```

## Conclusion
This project demonstrates how machine learning regression models can be used to estimate used car selling prices. The Random Forest Regressor achieved an R² score of 0.96 on the test set, while feature importance analysis identified present price as the dominant predictor.

## Author
**Muiz Takey**  
BE Computer Science and Engineering (AI & ML)