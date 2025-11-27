Insurance Claim Severity Prediction

A machine learning project that predicts the monetary severity of insurance claims based on customer attributes, vehicle information, and accident details. This repository contains a complete end-to-end workflow including data preprocessing, model training, evaluation, and prediction in a single Python file.

⸻

Overview

Accurate prediction of claim severity is a critical requirement for insurance companies. It enables better risk assessment, premium pricing, fraud detection, and overall portfolio management.
This project demonstrates a structured approach to building a regression pipeline using scikit-learn, covering:
	•	Data loading and cleaning
	•	Feature preprocessing (scaling and encoding)
	•	Model development (Random Forest and Gradient Boosting)
	•	Model evaluation (MAE and RMSE)
	•	Sample prediction workflow

The entire process is implemented in a single file:
insurance_claim_severity.py

⸻

Features
	•	Automated preprocessing with ColumnTransformer
	•	Support for both numerical and categorical features
	•	Two regression models for performance comparison
	•	Modular code design for extensibility
	•	Easy-to-run script structure
	•	Includes prediction on a sample claim instance

⸻

Requirements

Install the required dependencies using:

pip install -r requirements.txt

Suggested requirements.txt:

pandas
numpy
scikit-learn

Python version: 3.8+

⸻

Dataset

The script expects a CSV file named claims.csv in the same directory.

Example columns:

Column	Type	Description
age	numeric	Age of the policyholder
gender	string	Gender of the policyholder
vehicle_type	string	Type of insured vehicle
accident_severity	string	Reported severity of accident
claim_amount	numeric	Claim severity (target)

You may customize the dataset column names as needed.

⸻

How to Run
	1.	Place your dataset as claims.csv in the project directory.
	2.	Run the script:

python insurance_claim_severity.py

	3.	The script will:
	•	Load and preprocess data
	•	Split into train and test sets
	•	Train both models
	•	Evaluate performance
	•	Output a prediction for a sample input

⸻

Model Evaluation

The script reports the following metrics:
	•	Mean Absolute Error (MAE)
	•	Root Mean Squared Error (RMSE)

These metrics help assess model accuracy and generalization.

⸻

Project Structure

.
├── insurance_claim_severity.py
├── claims.csv
├── requirements.txt
└── README.md


⸻

Customization

You can extend this project by adding:
	•	Hyperparameter tuning (GridSearchCV, RandomizedSearchCV, Optuna)
	•	Additional models (XGBoost, LightGBM, CatBoost)
	•	Feature importance analysis
	•	Model persistence with joblib
	•	REST API (FastAPI or Flask)
	•	Web UI with Streamlit

I can generate any of these upon request.

⸻

License

This project is provided for educational and demonstration purposes.
This project is under MIT license.

⸻
