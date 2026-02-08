# HEART-DISEASE-PREDICTION

❤️ Heart Disease Prediction and Analysis using Explainable AI
📌 Overview
Heart disease remains one of the leading causes of death worldwide, making early detection and accurate risk assessment critical for improving survival rates. This project focuses on building an interpretable machine learning–based heart disease prediction system that not only predicts the likelihood of heart disease but also explains why a prediction was made.

Unlike traditional black-box models, this system emphasizes Explainable Artificial Intelligence (XAI) by integrating SHAP (SHapley Additive exPlanations) to identify and visualize the most influential risk factors. Additionally, the dataset is split by gender to capture biological and lifestyle differences between male and female patients, resulting in improved predictive performance.

🎯 Objectives

1. Predict the presence of heart disease using key patient health indicators
2. Improve prediction accuracy through feature selection and correlation analysis
3. Perform gender-specific modeling to capture distinct male and female risk patterns
4. Enhance model transparency using SHAP-based explainability
5. Provide a clinically interpretable and computationally efficient prediction system

🧠 Key Features
✅ Binary classification for heart disease prediction

✅ Gender-specific model training (Male / Female)

✅ Feature-to-feature correlation analysis

✅ SHAP-based explainability for model decisions

✅ Logistic Regression as a lightweight and interpretable model

✅ Google Colab–based implementation for accessibility

📂 Dataset
The model uses a heart disease dataset containing medical and demographic attributes such as:

Age
Sex
Chest pain type
Resting blood pressure
Serum cholesterol
Fasting blood sugar
Maximum heart rate achieved
ST depression
Exercise-induced angina
Preprocessing Steps
Removal of irrelevant and highly correlated features
Gender-based dataset splitting
Normalization and cleaning of input features

⚙️ Methodology
1️⃣ Exploratory Data Analysis

Correlation analysis between features and target variable
Gender-wise comparison of risk indicators
Visualization of key health metrics

2️⃣ Model Selection
Logistic Regression chosen for:

Interpretability
Efficiency in binary classification
Lower computational cost compared to ensemble models

3️⃣ Gender-Specific Modeling
Separate models trained for male and female datasets
Improved accuracy by capturing biological and behavioral differences
4️⃣ Explainability with SHAP
SHAP values used to:

Identify most influential features
Explain positive and negative contributions
Improve trust and transparency in predictions

📊 Results

1. Gender-specific models achieved higher accuracy compared to a single combined model.
2. Features such as age, cholesterol level, chest pain type, and ST depression had the strongest influence on predictions.
3. SHAP visualizations clearly highlighted positive and negative feature contributions for individual predictions.
4. Logistic Regression offered an effective balance between prediction performance and interpretability.

🖥️ User Interface

1. Designed with a clean and minimal layout for ease of use.
2. Includes clear input fields aligned with medical parameters.
3. Provides instant prediction output through a simple predict action.
4. Focuses on essential health indicators to reduce user complexity.

🛠️ Tech Stack

Python
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn
SHAP
Google Colab

🔍 Comparison with Existing Systems

Traditional systems often rely on black-box models with low interpretability, whereas this project provides clear explanations using SHAP.
Gender-specific risk patterns are explicitly modeled here, unlike many existing approaches.
Feature selection is dynamic and explainability-driven rather than static.
The system maintains low computational cost by using Logistic Regression instead of heavy ensemble models.
Clinical interpretability is significantly stronger, making results easier for healthcare professionals to trust and use.

🚀 Future Enhancements

1. Incorporate lifestyle-related features such as diet, physical activity, and stress levels.
2. Experiment with advanced machine learning models like Random Forest, XGBoost, and LightGBM.
3. Enable real-time prediction using wearable and IoT-based health data.
4. Deploy the system as a full-scale web or mobile healthcare application.
