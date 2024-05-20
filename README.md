### Air Quality Dataset - Regression Analysis
This project is part of the work completed during my first term in the AI & ML program at Lambton College. The focus is on performing a regression analysis on the Air Quality Dataset from the UCI Machine Learning Repository.

#### Overview
The Air Quality Dataset contains data from a monitoring station in an Italian city. The primary goal is to predict the concentration of pollutants based on various atmospheric conditions and chemical concentrations.

#### Objectives
- Perform a thorough exploratory data analysis (EDA).
- Preprocess the data to handle missing values and outliers.
- Build and evaluate regression models to predict pollutant concentrations.
- Interpret the results and identify key features influencing air quality.

#### Dataset Description
The dataset includes hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The variables in the dataset are:

Date: Date of the measurement.
Time: Time of the measurement.
CO(GT): True hourly averaged concentration of CO in mg/m^3 (reference analyzer).
PT08.S1(CO): Tin oxide chemical sensor response for CO.
NMHC(GT): True hourly averaged concentration of non-metanic hydrocarbons in microg/m^3 (reference analyzer).
C6H6(GT): True hourly averaged concentration of benzene in microg/m^3 (reference analyzer).
PT08.S2(NMHC): Tin oxide chemical sensor response for NMHC.
NOx(GT): True hourly averaged concentration of NOx in ppb (reference analyzer).
PT08.S3(NOx): Tungsten oxide chemical sensor response for NOx.
NO2(GT): True hourly averaged concentration of NO2 in microg/m^3 (reference analyzer).
PT08.S4(NO2): Tungsten oxide chemical sensor response for NO2.
PT08.S5(O3): Indium oxide chemical sensor response for O3.
T: Temperature in °C.
RH: Relative Humidity (%).
AH: Absolute Humidity.


### Regression Problem

The primary task is to predict the true hourly averaged concentration of CO (CO(GT)) using the other available features. This involves:

#### Data Cleaning and Preprocessing:
- Handling missing values and outliers.
- Feature engineering and selection.
- Scaling and normalizing data.

#### Exploratory Data Analysis (EDA):
- Visualizing data distributions and relationships.
- Identifying potential correlations between features.

#### Model Building:
- Implementing various regression algorithms such as Linear Regression, Decision Trees, Random Forest, and Gradient Boosting.
- Tuning hyperparameters for optimal performance.

#### Model Evaluation:
- Using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to evaluate model performance.
- Comparing different models and selecting the best-performing one.

#### Interpretation and Insights:
- Analyzing feature importances.
- Drawing conclusions about the key factors affecting CO concentration.

#### Tools and Libraries
- Python: The primary programming language used.
- Pandas: For data manipulation and analysis.
- Matplotlib & Seaborn: For data visualization.
- Scikit-learn: For implementing regression models and evaluation metrics.
- NumPy: For numerical operations.

Disclaimer: This was a group project.

