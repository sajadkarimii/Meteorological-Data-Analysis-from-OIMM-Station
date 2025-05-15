OIMM: Meteorological Data Analysis from OIMM Station
This repository contains a complete exploratory and statistical analysis of meteorological data collected from the OIMM station. The project is implemented using Python in Google Colab, with an emphasis on pattern detection, regression modeling, statistical testing, and data visualization.

📌 Project Objectives
The following analyses are performed in this notebook:

Detection of Seasonal Patterns for the VSBK (Visibility) feature.

Line Plot with Dual Axes for CLHL (Cloud Height Low Level) and VSBK in a single chart, along with intersection area calculation.

Comprehensive Tabular Report showing the mean and variance of all features, grouped by month and year.

Regression-based Forecasting of the average temperature for the last month in the dataset.

Correlation Analysis to investigate if there's a relationship between wind speed and cloud height.

AB Testing to determine whether the maximum annual average temperature change is statistically significant or random.

📂 Repository Structure
OIMM.ipynb: Main notebook containing the full code and analyses.

oimm.csv: The raw meteorological dataset.

README.md: Project documentation (you are reading it!).

🔍 Dataset Overview
The dataset (oimm.csv) contains meteorological observations with the following features (among others):

Date: Timestamp

TEMP: Temperature

WDSP: Wind Speed

CLHL: Cloud Height (Low)

VSBK: Visibility

PRCP: Precipitation

PRES: Atmospheric Pressure

📌 Feature names and values may be abbreviated. Refer to the dataset headers for full details.

🛠️ Technologies Used
Google Colab for development and execution

Python 3

Pandas for data manipulation

Matplotlib for visualization

Scikit-learn (sklearn) for regression modeling

Scipy.stats for statistical testing (AB test)

NumPy for numerical operations

▶️ How to Run
Open in Google Colab (recommended):


Or, clone the repo and run locally in Jupyter:

bash
Copy
Edit
git clone https://github.com/sajadkarimii/OIMM.git
cd OIMM
jupyter notebook OIMM.ipynb
📈 Key Analyses Explained
1. Seasonal Pattern Detection
The feature VSBK (Visibility) is grouped by month and visualized to uncover recurring seasonal patterns using boxplots and line trends.

2. Dual-Axis Line Plot + Area Calculation
A custom dual-axis line plot is created for features CLHL and VSBK. The shared area between the two lines is computed to quantify overlap in trends.

3. Monthly Feature Statistics
For every feature in the dataset, the mean and variance are calculated, grouped by month and year, and presented in a well-structured summary table.

4. Regression-Based Temperature Forecast
A regression model is trained using historical monthly averages to predict the average temperature of the last month in the dataset.

5. Correlation: Wind Speed vs Cloud Height
The relationship between WDSP (Wind Speed) and CLHL (Cloud Height Low Level) is assessed using scatter plots and correlation coefficients.

6. AB Test on Temperature Trends
The maximum annual average temperature is located, and an AB Test is performed to assess whether this change is statistically significant or random.

📊 Sample Output Visuals
Note: Visuals include line charts, scatter plots, statistical tables, and regression forecasts, all generated within the notebook.

📬 Contact
For questions, suggestions, or collaborations, please reach out via GitHub:
github.com/sajadkarimii

