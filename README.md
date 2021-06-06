### Credit Card Fraud Detection
* The [dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) contains 492 frauds out of 284,807 transactions. This is like 0.172% of all transactions. Ignoring this and building ML models based on the class label (1/0) will lead the algorithm to focus mainly on majority class label (non-fraud). Sampling methods such as **SMOTE**, Cost Sensitive Learning are used to overcome this issue. 

* We have built multiple ML algorithms and compared them with SMOTE applied dataset. Boosting algorithms such as XGBoost , lightGBM are evaluated based on PR,ROC Curves.

* **Random Forest, XGBoost** with cross validation are performing well on SMOTE data and produced highest PR values (both 0.9989) followed by **LightGBM** (it took less time to train compared to XGBoost and produced good results)



