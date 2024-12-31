
# Cirrhosis Patient Survival Prediction

## Objective
This project aims to predict the survival of patients diagnosed with cirrhosis using various machine learning models.

## Methodology
The notebook explores data preprocessing techniques, feature engineering, model training, and evaluation to achieve accurate predictions for cirrhosis patient survival.

## Key Features
- Handles missing values using **SimpleImputer** and **fill_constant** strategies.
- Encodes categorical variables for machine learning compatibility.
- Scales features to enhance model performance, especially for distance-based models like KNN.
- Employs complex models like **CatBoost** and **XGBoost**.
- Uses hyperparameter tuning to optimize model performance and prevent overfitting/underfitting.

## Prerequisites
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, catboost, xgboost, matplotlib, seaborn, etc.

## How to Run
1. Clone the repository or download the notebook.
2. Install the required libraries using:
   ```
   pip install pandas numpy scikit-learn catboost xgboost matplotlib seaborn

   ```
3. Open the notebook and run all cells to reproduce the analysis.

## Insights
- Most data consists of numerical types, with significant missing values in both training and test datasets.
- Imputing missing data and scaling features are crucial for improving model performance.
- **CatBoost** and **XGBoost** performed the best among tested models.

## Future Work
- Explore advanced imputation methods, such as predictive modeling for missing data.
- Address class imbalance for improved predictions of minority classes.

## Author
Emery Fathan Zwageri

---