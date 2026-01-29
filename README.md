Accurate Fraudulent Transaction Detection is very important task for both safety-security and customer satisfaction

This project applied several supervised learning algorithms like: Logistic Regression, Naive Bayes, Random Forest, Extra Trees, CatBoost, XGBoost and LightGBM as well as an unsupervised learning algorithm called Isolation Forest.
A lesser knowm algorithm called Extra Trees Classifier emerged as the top model for classification with the highest Recall with Random Forest being the close second (has a higher roc-auc score).
LightGBM however proved to have most capability to accurately classify fraudulent transactions even though it had a lower recall and auc-roc score.
Other supervised learning algorithms like Support Vector Machine and TabNet were exempted beacuse of their extremely slow convergence.

The dataset is really big (6.35 million samples) and with extreme class imbalance. So working with it gave me an idea of the limitations of pandas and local machines/hardwares
