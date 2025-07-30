❤️ Heart Disease Classification

This is a-friendly machine learning project that predicts whether a patient is likely to have heart disease, using Python and supervised learning models.

📝 Project Description
This project is based on a public heart disease dataset and demonstrates a full end-to-end machine learning pipeline. It includes:

📥 Data loading using pandas

📊 Exploratory Data Analysis (EDA) using Seaborn and Matplotlib

✂️ Train-test split using train_test_split from sklearn

🤖 Model training with:

Random Forest Classifier

Logistic Regression

🧪 Model evaluation using:

1-Accuracy

2-Precision

3-Recall

4-F1 Score

5-Confusion matrix

6-Classification report

🔍 Hyperparameter tuning using RandomizedSearchCV for the Random Forest model

💾 Model saving with joblib

✅ This project is ideal for learning binary classification, model evaluation metrics, and hyperparameter tuning using scikit-learn.

🛠️ How to Run
Make sure you have Python 3.8+ installed

Clone the repository and navigate to the project directory

Create and activate a virtual environment:

bash
Copy
Edit
python -m venv heart
source heart/bin/activate      # On Linux/Mac
.\heart\Scripts\activate       # On Windows
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook "Simple-ML Heart.ipynb"
📁 Project Structure
bash
Copy
Edit
heart-disease-classification/
│
├── data/
│   └── heart-disease.csv               # Dataset
│
├── Simple-ML Heart.ipynb               # Main notebook with full ML pipeline
├── requirements.txt                    # List of dependencies
└── README.md                           # Project description

