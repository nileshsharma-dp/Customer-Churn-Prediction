# 📉 Telco Churn Classification Project

**Customer churn** is one of the most important metrics for a growing business to evaluate. It’s far more cost-effective to retain an existing customer than to win one back after they’ve left. Understanding and preventing customer churn is critical to long-term business success.

In this project, we use statistical testing and machine learning to identify key factors influencing churn, develop a predictive classification model, and provide actionable recommendations to reduce customer loss.

---

## 🧠 Technologies & Tools Used

- **Programming Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, imbalanced-learn, SciPy  
- **Modeling**: Decision Tree Classifier  
- **Imbalance Handling**: SMOTEENN (SMOTE + Edited Nearest Neighbors)
- **Dataset**: WA_Fn-UseC_-Telco-Customer-Churn.csv  
- **Problem Type**: Classification  
- **Goal**: Predict whether a customer will churn or not  
- **ML Algorithm Used**: Decision Tree Classifier  
- **Handling Imbalance**: SMOTEENN (Hybrid of Oversampling and Cleaning)

---

## 📁 Files in this Repository

- `Churn_prediction_model.ipynb`: The original model notebook  
- `Churn_prediction_model_with_comments.ipynb`: Annotated version of the notebook with clear comments  
- `README.md`: Project documentation (this file)

---

## 💼 Business Goals

- Identify key drivers of customer churn at a telecom company  
- Construct a machine learning classification model to predict churn  
- Deliver a comprehensive report that a non-technical audience can understand  
- Provide churn predictions for a given customer list (via CSV)

---

## 📝 Initial Questions

- Which features are most associated with churn?  
- Do customers who churn pay higher monthly charges?  
- Do churned customers have shorter tenure?  
- Are optional/add-on services related to churn?  

---

## 📊 Data Dictionary

| Feature                | Type                         | Description |
|------------------------|------------------------------|-------------|
| `Contract`             | Categorical (3 types)        | Type of contract (Month-to-month, One year, Two year) |
| `InternetService`      | Categorical (3 types)        | Type of internet service (DSL, Fiber optic, None) |
| `PaymentMethod`        | Categorical (4 types)        | Payment method used (Bank, Credit Card, etc.) |
| `MonthlyCharges`       | Continuous                   | Monthly bill amount |
| `Tenure`               | Integer                      | Number of months the customer has stayed |
| `OnlineBackup`         | Categorical (Yes/No/None)    | Whether customer uses online backup |
| `OnlineSecurity`       | Categorical (Yes/No/None)    | Whether customer uses online security |
| `TechSupport`          | Categorical (Yes/No/None)    | Whether customer has tech support |
| `DeviceProtection`     | Categorical (Yes/No/None)    | Whether customer has device protection |
| `StreamingTV`          | Categorical (Yes/No/None)    | Whether customer uses streaming TV |
| `StreamingMovies`      | Categorical (Yes/No/None)    | Whether customer uses streaming movies |
| `Churn`                | Binary                       | Target variable: Did the customer churn? |

---

## 🪧 Process

### 1️⃣ Data Acquisition
- Load and explore the Telco customer churn dataset

### 2️⃣ Data Preparation
- Handle missing values, drop irrelevant columns, and encode categorical variables  
- Balance the dataset using **SMOTEENN**

### 3️⃣ Exploratory Data Analysis
- Analyze distributions and relationships between variables and churn  
- Visualize churn rates across various features using seaborn & matplotlib

### 4️⃣ Statistical Testing & Modeling
- Conduct hypothesis tests (t-test, chi-square) to validate feature importance  
- Train a **Decision Tree Classifier**  
- Evaluate using confusion matrix, classification report, and recall score

### 5️⃣ Model Evaluation
- Measure accuracy, recall, and precision  
- Focus on recall to catch most of the customers likely to churn  
- Optionally test other models like Logistic Regression or Random Forest

---

## 🔁 Reproducibility

1. Clone this repository  
2. Install dependencies:

   pip install -r requirements.txt

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Author
Nilesh Sharma – GitHub Profile


