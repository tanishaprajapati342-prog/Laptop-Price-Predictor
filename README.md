# 💻 Laptop Price Prediction 

This project focuses on analyzing historical laptop configuration data, uncovering pricing trends, building robust predictive models, and deploying an interactive web application using **Streamlit**.

## 📌 Project Objectives

- Clean and preprocess raw laptop specifications dataset
- Perform in-depth Exploratory Data Analysis (EDA)
- Visualize key pricing trends (Brand, RAM, CPU, GPU, Storage, Weight, etc.)
- Engineer features for better model performance
- Train and evaluate multiple machine learning regression models
- Optimize the best model using Hyperparameter Tuning
- Deploy an interactive user interface using **Streamlit** for real-time price prediction

## 🧠 Key Learnings

- Advanced data preprocessing (handling missing values, categorical encoding, and feature scaling)
- Analyzing feature importance using tree-based regressors
- Comparing multiple regression algorithms to find the best fit
- Hyperparameter tuning using GridSearchCV
- Evaluating models using metrics: MAE, MSE, RMSE, and $R^2$ Score
- Building and deploying a web interface with Streamlit and Pickle model serialization

## 🛠️ Tools & Technologies

- **Languages:** Python  
- **Web Framework:** Streamlit  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Modeling:** Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, SVR  
- **Tuning:** GridSearchCV  
- **Deployment / Tools:** Jupyter Notebook, VS Code, Git & GitHub

## 📊 Exploratory Data Analysis

- Visualized price trends across various laptop brands, screen sizes, and hardware configurations.
- Discovered that **RAM capacity**, **CPU performance**, **GPU type**, and **SSD storage** have the highest impact on the selling price.
- Feature engineering helped significantly improve model prediction accuracy.

## 🔍 Model Building & Evaluation

| Model                 | MAE    | MSE     | RMSE    | $R^2$ Score |
|----------------------|--------|---------|---------|-------------|
| Linear Regression     | ...    | ...     | ...     | ...         |
| Ridge Regression      | ...    | ...     | ...     | ...         |
| Lasso Regression      | ...    | ...     | ...     | ...         |
| Decision Tree         | ...    | ...     | ...     | ...         |
| Random Forest         | ...    | ...     | ...     | ...         |
| SVR                   | ...    | ...     | ...     | ...         |

✅ The **best-performing model** based on generalization and accuracy was: **[Your Best Model Here, e.g., Random Forest]**

## 🚀 Streamlit Web Application

The trained model is integrated into an interactive web app where users can input specs (Brand, Type, RAM, Weight, Touchscreen, CPU, Storage, GPU, OS) to get instant price predictions.

To run the app locally:
```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the Streamlit app
streamlit run app.py
