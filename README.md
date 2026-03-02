# SpaceX Falcon 9 First Stage Landing Prediction

## Applied Data Science Capstone Project
**IBM Data Science Professional Certificate - Coursera**

## Project Overview

This capstone project predicts whether the SpaceX Falcon 9 first stage will successfully land after launch. SpaceX's ability to reuse the first stage reduces launch costs from $165M to approximately $62M. Accurate landing predictions help competing launch providers determine fair pricing when bidding against SpaceX.

## Repository Structure

```
├── README.md
├── notebooks/
│   ├── 01_data_collection_api.ipynb           # Data Collection via SpaceX REST API
│   ├── 02_data_collection_webscraping.ipynb    # Data Collection via Wikipedia Web Scraping
│   ├── 03_data_wrangling.ipynb                 # Data Cleaning and Feature Engineering
│   ├── 04_eda_sql.ipynb                        # Exploratory Data Analysis with SQL
│   ├── 05_eda_visualization.ipynb              # EDA with Matplotlib and Seaborn
│   ├── 06_interactive_map_folium.ipynb         # Interactive Map Visualization with Folium
│   ├── 07_spacex_dash_app.py                   # Interactive Dashboard with Plotly Dash
│   └── 08_machine_learning_prediction.ipynb    # Predictive Analysis with Classification Models
└── presentation/
    └── SpaceX_Falcon9_Landing_Prediction.pdf   # Final Project Presentation
```

## Methodology

1. **Data Collection** - SpaceX REST API and Wikipedia web scraping (BeautifulSoup)
2. **Data Wrangling** - Missing value handling, target variable creation, one-hot encoding
3. **EDA with SQL** - Aggregation queries on launch data using SQLite
4. **EDA with Visualization** - Scatter plots, bar charts, trend analysis (Matplotlib/Seaborn)
5. **Interactive Visual Analytics** - Folium maps and Plotly Dash dashboard
6. **Predictive Analysis** - Logistic Regression, SVM, Decision Tree, KNN with GridSearchCV

## Key Findings

- Landing success rate improved from ~33% (2013) to ~90%+ (2020)
- KSC LC-39A has the highest success rate (77.4%)
- Orbit type is the strongest predictor (LEO/ISS/SSO: ~100%, GTO: ~56%)
- **Decision Tree classifier achieved the best accuracy: 87.5%**

## Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Folium, Plotly Dash, Scikit-learn, SQL, Jupyter Notebooks
