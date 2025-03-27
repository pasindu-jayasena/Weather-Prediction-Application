# 🌦️ **Predicting Weather Conditions in Sri Lanka** 🌦️

## 📜 **Project Overview**
This project predicts the **Weather Code** (0 for **Sunny**, 1 for **Rainy**, 2 for **Cloudy**) using historical weather data from **30 cities in Sri Lanka** (2010-2023). By analyzing past weather patterns, the model will help classify future weather conditions, ultimately assisting in **better planning** for weather-dependent activities.

---
## 📊 **Dataset Information**
**Data Source**: [Sri Lanka Weather Dataset](https://www.kaggle.com/datasets/rasulmah/sri-lanka-weather-dataset)

The dataset includes **24 features** and a **target variable**: `weathercode`. Here's a breakdown of the dataset:

- **time**: Timestamp of each weather observation.
- **weathercode**: Numerical code representing the weather conditions (**target variable**).
- **temperature_2m_max**: Max temperature at 2 meters.
- **temperature_2m_min**: Min temperature at 2 meters.
- **temperature_2m_mean**: Mean temperature at 2 meters.
- **apparent_temperature_max**: Max apparent temperature (includes wind chill or heat index).
- **apparent_temperature_min**: Min apparent temperature.
- **apparent_temperature_mean**: Mean apparent temperature.
- **sunrise**: Time of sunrise.
- **sunset**: Time of sunset.
- **shortwave_radiation_sum**: Sum of shortwave radiation.
- **precipitation_sum**: Total precipitation (rain + snow).
- **rain_sum**: Total rainfall.
- **snowfall_sum**: Total snowfall.
- **precipitation_hours**: Duration of measurable precipitation.
- **windspeed_10m_max**: Max wind speed at 10 meters above ground.
- **windgusts_10m_max**: Max wind gusts at 10 meters above ground.
- **winddirection_10m_dominant**: Dominant wind direction at 10 meters.
- **et0_fao_evapotranspiration**: Reference evapotranspiration (FAO Penman-Monteith).
- **latitude**: Latitude of each city.
- **longitude**: Longitude of each city.
- **elevation**: Elevation of each city.
- **country**: Name of the country.
- **city**: Name of the city.

---

## 🛠️ **Methodology**:
### 1. **Exploratory Data Analysis (EDA)**:
   - Initial inspection of the dataset to uncover trends, missing values, and outliers.

### 2. **Data Preprocessing**:
   - Cleaning and transforming data to prepare it for model training.

### 3. **Modeling**:
   - Applied **Logistic Regression** and **Random Forest** to predict weather conditions.

### 4. **Model Evaluation**:
   - Cross-validation for assessing model performance.
   - **Mean accuracy** and **standard deviation** calculated.
   - Evaluation accuracy results for each model.

---

## 📈 **Results**:

### Logistic Regression:
- **Mean CV Accuracy**: 92%
- **Standard Deviation**: 1%
- **Model Accuracy**: 77%

### Random Forest:
- **Mean CV Accuracy**: 92%
- **Standard Deviation**: 1%
- **Model Accuracy**: 87%

---

## 🚀 **Conclusion**:
The **Random Forest** model outperformed **Logistic Regression** in terms of accuracy, achieving **87%** accuracy in predicting the weather conditions. This project demonstrates the power of machine learning in weather forecasting and can be extended to other regions or refined for specific use cases like **event planning** or **agricultural management**.

---


## 🔗 **References**:
- [Kaggle Weather Dataset](https://www.kaggle.com/datasets/rasulmah/sri-lanka-weather-dataset)
