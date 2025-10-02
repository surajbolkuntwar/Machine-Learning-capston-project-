# Bank Customer Churn Prediction (Capstone ML Project)

This project aims to predict whether a bank customer is likely to churn (leave the bank) using supervised machine learning techniques.  
Customer churn prediction helps financial institutions identify at-risk customers and take proactive steps to improve retention and reduce revenue loss.  



## Project Description
- Developed a churn prediction model using multiple machine learning algorithms:
  - Logistic Regression  
  - Random Forest  
  - Decision Tree Classifier  
  - K-Nearest Neighbors (KNN)  
  - Gradient Boosting  
  - AdaBoost  
  - XGBoost  

- **Gradient Boosting** was selected as the best-performing model due to its higher accuracy compared to other models.  

- Model Performance:  
  - **Train Accuracy**: 86.3%  
  - **Cross-Validation Score**: 86.2%  
  - **Test Accuracy**: 84.5%  



## Tools & Libraries
- **Programming Language**: Python  
- **Libraries**: Pandas, Numpy, XGBoost, Matplotlib, Seaborn  


## Workflow
1. **Data Preprocessing** – cleaned data, encoded categorical variables, and performed feature transformation.  
2. **Exploratory Data Analysis (EDA)** – visualized feature distributions and their relationship with churn.  
3. **Model Building** – trained and evaluated multiple ML models.  
4. **Model Evaluation** – compared models using accuracy and cross-validation scores.  
5. **Final Selection** – Gradient Boosting chosen as the best model.  



## Results & Insights
- The final model achieved a **Test Accuracy of 84.5%**.  
- Key factors influencing churn included:  
  - Customer credit score  
  - Account balance  
  - Tenure with the bank  
  - Number of products held  
