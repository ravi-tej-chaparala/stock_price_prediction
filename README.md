# Stock Price Prediction Using Logistic Regression

## Project Overview

This project uses a logistic regression model to predict stock price movement based on four years of historical stock data. Features such as `open-close`, `low-high`, and `is_quarter_end` were engineered to enhance the model's predictive power.

### Key Steps
- **Data Preprocessing**: Cleaned the dataset, removed redundant columns, and created new features.
- **Feature Engineering**: Added features like the difference between the opening and closing prices, and identified if the date was a quarter-end.
- **Model**: Trained a logistic regression model and evaluated it using ROC-AUC and a confusion matrix.

### Results
- **Training ROC-AUC Score**: 0.54
- **Validation ROC-AUC Score**: 0.58
- The model’s accuracy suggests the need for more complex models to improve prediction performance.

## Future Work
- Experiment with advanced models like Random Forests or LSTMs.
- Incorporate more financial indicators and hyperparameter tuning to improve results.
