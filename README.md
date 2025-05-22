Credit Card Fraud Detection using Logistic Regression

This project aims to detect fraudulent credit card transactions using Logistic Regression, a supervised machine learning algorithm. The model is trained and evaluated on real-world anonymized transaction data to identify suspicious activity based on patterns in the data.

📝 Table of Contents
About the Project

Dataset

Technologies Used

How It Works

Installation & Setup

Results

Conclusion

License

📌 About the Project
Credit card fraud is a growing problem in the financial sector, causing billions of dollars in losses each year. This project demonstrates how machine learning—specifically logistic regression—can help detect and classify transactions as fraudulent or genuine based on historical data.

📊 Dataset
Source: Kaggle - Credit Card Fraud Detection

Description: The dataset contains transactions made by European cardholders in September 2013. It has 284,807 transactions, of which 492 are frauds.

Features: 30 numerical input features including Time, Amount, and 28 PCA-transformed variables (V1 to V28).

Imbalanced Classes: Only 0.17% of the transactions are fraud.

🛠️ Technologies Used
Python 3.x

Pandas for data manipulation

NumPy for numerical operations

Matplotlib & Seaborn for data visualization

Scikit-learn for machine learning

⚙️ How It Works
Data Loading – Load the dataset using Pandas.

Data Preprocessing:

Normalize the Amount feature.

Drop or retain necessary columns.

Split into features (X) and labels (y).

Train-Test Split – Use an 80/20 or stratified split due to class imbalance.

Model Training – Train Logistic Regression model using sklearn.linear_model.

Prediction & Evaluation:

Accuracy, Precision, Recall, F1-score

Confusion Matrix

ROC-AUC Curve

Class Imbalance Handling:

Use class_weight='balanced' in Logistic Regression

OR apply undersampling/oversampling (SMOTE)


📈 Results
The logistic regression model achieved the following results (example metrics):

Accuracy: 98.9%

Precision: 91.4%

Recall (Sensitivity): 87.6%

F1-score: 89.5%

ROC AUC: 0.96

These values may vary depending on preprocessing and sampling strategies.


