# Wait-Time-Forecasting-
This project involves developing machine learning models to predict wait times for attractions at the EU Park. The dataset used contains various features including date, temperature, and historical wait times.

## Data Processing and Exploration
1. Initial Data Exploration: The initial step involved loading the dataset and performing exploratory data analysis to understand the data's characteristics.
2. Data Cleaning and Transformation: I focused on handling outliers in the 'WaitTime' column and converting the 'Date' column to datetime format for time series analysis.
3. Feature Engineering: The project included creating new features and transforming existing ones to better suit the models.

## Models Used
1. **Random Forest Regressor**: A robust model for handling non-linear relationships and interactions between features.
2. **Comprehensive ARIMA Model**: Implemented for its effectiveness in time series forecasting, considering trends and seasonality in data.
3. **Basic Average Ensemble Model**: A simple ensemble method combining predictions from the Random Forest and ARIMA models.

## Model Evaluation
1. Each model was evaluated based on metrics like RMSE, MAE, and R2.
2. The ARIMA model exhibited the highest accuracy, making it the preferred choice for forecasting wait times in this context.

## Conclusion and Future Work
This project demonstrates the application of machine learning in optimizing theme park experiences. Future enhancements could include integrating more dynamic features such as weather forecasts, special event schedules, and real-time updates from the park.
