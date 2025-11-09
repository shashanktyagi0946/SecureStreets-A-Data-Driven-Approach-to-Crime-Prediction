# SecureStreets 🚦
**Author:** Shashank Tyagi

## Overview
**SecureStreets** is a data-driven project aimed at predicting **crime hotspots** and **crime types** across the UK using spatial and temporal crime data.
By analyzing historical datasets containing longitude, latitude, and time-based features, the model provides insights that can help law enforcement agencies allocate resources efficiently and enhance community safety.

---

## Objectives
* Predict areas with a high likelihood of criminal activity (hotspot prediction).
* Identify the most probable crime types based on location and time.
* Visualize spatial patterns and trends using geospatial tools.

---

## Dataset
The project utilizes publicly available crime data from the **UK Government’s open data portal**.
The dataset includes attributes such as:
* Crime type
* Location (longitude, latitude, LSOA code)
* Date and time of crime occurrence

---

## Methodology
1.  **Data Preprocessing** — cleaning, encoding categorical data, and scaling features.
2.  **Exploratory Data Analysis (EDA)** — identifying trends and geographical distributions using `matplotlib`, `seaborn`, and `folium`.
3.  **Feature Engineering** — transforming temporal and spatial data for modeling.
4.  **Model Building** — experimenting with multiple models including:
    * Random Forest Regressor
    * Stacking Regressor
    * Neural Networks (TensorFlow/Keras)
5.  **Evaluation** — using metrics such as RMSE, MAE, and R² Score to assess performance.
6.  **Visualization** — generating interactive maps and charts to represent results.

---

## Tools & Libraries
The following Python libraries were used in the project:
* **pandas**
* **numpy**
* **matplotlib**
* **seaborn**
* **scikit-learn**
* **tensorflow**
* **geopandas**
* **folium**
* **google-auth**

To install all dependencies, run:
bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow geopandas folium google-auth
Project Structure
Bash

SecureStreets-A-Data-Driven-Approach-to-Crime-Prediction/
│
├── data/                       # Datasets used for training/testing
├── notebooks/                  # Jupyter notebooks (including final project notebook)
│   └── Copy of Group13_DataScience_Project_Final.ipynb
├── results/                    # Plots, reports, and maps
└── README.md
How to Run
Clone this repository:

Bash

git clone [https://github.com/shashanktyagi0946/SecureStreets-A-Data-Driven-Approach-to-Crime-Prediction.git](https://github.com/shashanktyagi0946/SecureStreets-A-Data-Driven-Approach-to-Crime-Prediction.git)
cd SecureStreets-A-Data-Driven-Approach-to-Crime-Prediction
Install dependencies (if not already installed):

Bash

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow geopandas folium google-auth
Launch Jupyter Notebook and open:

Bash

jupyter notebook "Copy of Group13_DataScience_Project_Final.ipynb"
Run all cells sequentially to reproduce the analysis and model results.

Results
The model successfully identifies high-risk areas and predicts likely crime types based on spatial and temporal factors. Interactive maps generated using folium help visualize these patterns effectively and highlight areas that may require increased attention from law enforcement.

Future Work
Integrate real-time data streams for live hotspot prediction.

Improve model accuracy with deep learning and ensemble learning methods.

Build an API or interactive dashboard for public access and insights.

License
This project is licensed under the MIT License — feel free to use, modify, and share it for academic or research purposes.
