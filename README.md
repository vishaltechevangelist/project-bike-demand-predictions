# Bike Demand Prediction - Capital Bikeshare

## 📌 Project Description
This project aims to predict the hourly demand for bike rentals using the **Capital Bikeshare** dataset from Kaggle.  
It is a regression problem where the target variable is the number of bikes rented in a given hour.  
The model helps understand how factors like weather, season, holidays, and time of day influence bike demand.  

By accurately forecasting demand, bike-sharing companies can:
- Optimize bike distribution across stations
- Reduce shortages and surpluses
- Improve operational efficiency

---

## 📊 Dataset Details
The dataset contains historical usage patterns of the Capital Bikeshare program, including environmental and seasonal factors.  

**Key Variables:**
- **datetime** – Date and time of the record
- **season** – Season of the year (1 = spring, 2 = summer, 3 = fall, 4 = winter)
- **holiday** – Whether the day is a holiday (1 = yes, 0 = no)
- **workingday** – Whether the day is a working day (1 = yes, 0 = no)
- **weather** – Weather situation (1 = clear, 2 = cloudy, 3 = light snow/rain, 4 = heavy rain/snow)
- **temp** – Normalized temperature in Celsius
- **atemp** – Normalized "feels-like" temperature in Celsius
- **humidity** – Normalized humidity level
- **windspeed** – Normalized wind speed
- **count** – Total number of bike rentals (target variable)

---

## 🔍 Activities Performed
1. **Data Loading & Exploration**
   - Import dataset from Kaggle
   - Check for missing values and data types
   - Visualize trends and relationships between variables

2. **Data Preprocessing**
   - Convert datetime to separate features (hour, day, month, year)
   - Encode categorical variables (season, weather, etc.)
   - Scale numerical variables where required

3. **Model Development**
   - Split data into train and test sets
   - Train multiple regression models (Linear Regression, Random Forest, Gradient Boosting, XGBoost)
   - Perform hyperparameter tuning

4. **Evaluation**
   - Use **R² score** and **RMSE** for model performance
   - Plot actual vs. predicted bike demand

5. **Prediction**
   - Generate predictions on test set
   - Visualize prediction trends

---

## 📈 Expected Outcome
- A trained model that can accurately predict bike rental demand
- Insights into which factors most influence bike usage
- Visualizations to support operational decision-making

---
