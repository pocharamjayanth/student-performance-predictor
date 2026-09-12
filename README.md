🎯 Project Overview
This project is an end-to-end AI/ML and data analytics application designed to predict student academic performance. Tailored for data analyst roles, it highlights rigorous exploratory data analysis (EDA), data cleaning, feature visualization, and deep academic insight generation on a real dataset.

🛠️ Tools & Tech Stack
Data Processing & Wrangling: Pandas and NumPy for cleaning, missing-value imputation, and dataset structuring.

Exploratory Data Analysis & Visualization: Matplotlib and Seaborn for uncovering behavioral patterns, feature distributions, and correlations.

Machine Learning & Persistence: Scikit-Learn (Linear Regression and Random Forest) and Joblib for robust model training, evaluation, and serialization (.pkl files).

Application Framework: Flask and HTML for deploying a user-friendly, real-time web interface.

📊 Academic Insights & Findings
Attendance Impact: Exploratory data analysis demonstrated that attendance percentage acts as a primary performance divider, cleanly separating passing and failing student profiles.

Habit Equilibrium: Visualizations revealed a direct relationship between balanced study hours and continuous grade points, emphasizing that monitoring sleep duration prevents skewed performance predictions.

Actionable Dual-Output: Combining regression (continuous grade prediction) with classification (pass/fail status) establishes a dual-layered risk assessment tool capable of supporting early academic intervention.

📂 Repository Structure
/data: Cleaned and raw datasets used for exploratory analysis and model training

/models: Serialized .pkl model assets ready for inference

/notebooks: Detailed Jupyter Notebooks covering EDA, feature engineering, and model tuning

/templates: HTML templates powering the Flask application interface

