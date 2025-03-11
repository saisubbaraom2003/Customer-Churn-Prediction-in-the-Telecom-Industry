# 📌 Customer Churn Prediction in the Telecom Industry

## 📖 Project Overview
Customer churn is a major concern in the telecom industry. This project aims to predict whether a customer will churn (leave the service) based on various factors such as contract type, monthly charges, tenure, and service usage. By leveraging Machine Learning, we build predictive models to help telecom companies identify at-risk customers and take proactive retention measures.

## 📂 Dataset Information
The dataset consists of telecom customer records with both numerical and categorical features:
- **customerID**: Unique identifier for each customer
- **gender**: Male or Female
- **SeniorCitizen**: 1 if senior citizen, 0 otherwise
- **Partner, Dependents**: Relationship status indicators
- **tenure**: Duration (in months) with the company
- **PhoneService, MultipleLines**: Subscription details for phone services
- **InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies**: Internet-related features
- **Contract**: Subscription type (Month-to-month, One year, Two years)
- **PaymentMethod**: Mode of payment
- **MonthlyCharges, TotalCharges**: Financial details
- **Churn**: Target variable (Yes/No)

## 🚀 Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Converting categorical variables using **pd.get_dummies**
   - Scaling numerical features using **MinMaxScaler**
2. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions
   - Identifying patterns affecting customer churn
3. **Model Training & Evaluation**
   - Tried multiple classifiers: **Logistic Regression, Decision Tree, Random Forest, XGBoost, SVM, KNN, Naïve Bayes**
   - Implemented **Logistic Regression** for ensemble learning
   - Used **Stratified Train-Test Split (80-20)**
   - Evaluated models using **Accuracy, Precision, Recall, F1-score**

## 📊 Model Performance
| Model               | Train Accuracy | Test Accuracy |
|---------------------|---------------|--------------|
| Logistic Regression | 80.42%        | 79.84%       |
| Decision Tree      | 99.80%        | 73.88%       |
| Random Forest      | 99.79%        | 78.64%       |
| XGBoost           | 93.88%        | 78.14%       |
| KNN               | 83.49%        | 74.80%       |
| SVM               | 82.05%        | 78.92%       |
| Naïve Bayes       | 66.54%        | 65.58%       |




## 📌 Key Insights
- Customers with **month-to-month contracts** are more likely to churn.
- **Higher monthly charges** are correlated with higher churn rates.
- Customers with **no tech support or online security** tend to leave more.
- **Longer tenure** customers are less likely to churn.

## 🏆 Conclusion
This project successfully predicts customer churn using Machine Learning models. The insights can help telecom companies design better customer retention strategies by targeting at-risk customers and improving their services.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Connect with Me
Feel free to reach out for collaborations or discussions:
- **GitHub**: [Sai Subba Rao Mahendrakar](https://github.com/saisubbaraom2003)
- **Contact Me**: [sai.subbu.in@gmail.com](sai.subbu.in@gmail.com)

---
⭐ If you found this project helpful, give it a star on GitHub! ⭐
