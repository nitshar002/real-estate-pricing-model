# Real Estate Valuation Engine & Streamlit Dashboard

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://idx-ds43-housing-app.streamlit.app/)

> **Live Demo:** Explore the interactive model interface at [idx-ds43-housing-app.streamlit.app](https://idx-ds43-housing-app.streamlit.app/)
>
> 
An end-to-end machine learning pipeline that predicts residential property values using gradient boosting (LightGBM). Built with an automated object-oriented ETL pipeline and served via an interactive Streamlit web application.

---

## Key Results & Impact

* **Model Performance:** Achieved an **$R^2$ of 91.04%** and a Median Absolute Percentage Error (**MdAPE) of 7.55%** using LightGBM regression.
* **Dimensionality Reduction:** Refactored spatial features from over 1,000 sparse one-hot encoded variables into custom target-encoding classes, boosting model performance by **15–20%**.
* **Data Integrity:** Designed an automated Python ETL pipeline processing 100K+ records with strict validation checks to eliminate target leakage prior to training.

