# SpaceX Falcon 9 Landing Prediction -- Applied-Data-Science-Capstone-IBM

## Overview

This project aims to predict the success of SpaceX Falcon 9 first-stage rocket landings using machine learning techniques. Successful landings are critical for reducing launch costs through rocket reusability. This repository contains notebooks for each step of the project, including data collection, data wrangling, exploratory data analysis (EDA), and building predictive models.

## Project Structure

- **Executive Summary**: Provides an overview of the project's goal, approach, and key outcomes.
- **Introduction**: Details the motivation behind the project, including the importance of Falcon 9's reusability.
- **Methodology**: Outlines the data collection process, including the SpaceX API and web scraping, and the machine learning models used.
- **Results**: Includes model accuracy, insights from the predictive analysis, and key factors influencing landing success.
- **Conclusion**: Summarizes findings and discusses potential future improvements.

## Notebooks

### 1. [Data Collection - SpaceX API](https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM/blob/main/jupyter-labs-spacex-data-collection-api.ipynb)
   - Collects historical launch data from the SpaceX API, including details such as booster version, launch site, payload mass, and landing outcome.

### 2. [Data Collection - Web Scraping](https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM/blob/main/jupyter-labs-webscraping.ipynb)
   - Scrapes additional data points to enhance the dataset used for predictions.

### 3. [Data Wrangling](https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM/blob/main/edadataviz.ipynb)
   - Cleans and formats the data, handling missing values and ensuring it’s structured for analysis.

### 4. [Exploratory Data Analysis (EDA) with Data Visualization](https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM/blob/main/jupyter-labs-eda-sql-coursera_sqllite.ipynb)
   - Visualizes key trends, relationships between payload and orbit type, and more using Python libraries such as Matplotlib and Seaborn.

### 5. [Interactive Maps and Dashboards](https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM/blob/main/lab_jupyter_launch_site_location.ipynb)
   - Creates interactive maps using Folium and dashboards with Plotly Dash to visualize launch sites and success rates.

### 6. [Predictive Analysis (Classification Models)](https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM/blob/main/SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb)
   - Builds and evaluates machine learning classification models (Logistic Regression, Decision Trees, etc.) to predict the likelihood of successful landings.

## Key Features

- **Data Wrangling**: Removed missing values, transformed data types, and scaled features for modeling.
- **EDA**: Insights into key factors like booster reuse, grid fins, and landing geography.
- **Machine Learning Models**: Built and evaluated several classification models to predict landing outcomes.
- **Interactive Dashboards**: Visualized data using interactive tools to explore landing success.

## Conclusion

The project successfully demonstrates the use of machine learning to predict SpaceX Falcon 9 landings, which is crucial for reducing costs through reusability. The results show strong predictions based on key features, and future improvements could include expanding the dataset and refining the hyperparameters of the models.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mohannadtazi/Applied-Data-Science-Capstone-IBM.git
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

