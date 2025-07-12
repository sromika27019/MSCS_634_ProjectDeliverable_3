# Deliverable 3 – Classification, Clustering, and Pattern Mining

## Overview

In this deliverable, I focused on applying machine learning techniques such as classification, clustering, and association rule mining to analyze customer behavior based on age, income, and spending score. The goal was to explore patterns and build predictive models to better understand the data.

---

## Classification Models

I built two classification models:
- **Decision Tree Classifier**
- **k-Nearest Neighbors (k-NN)**

After evaluating both models, I found that k-NN performed better, especially after applying hyperparameter tuning using GridSearchCV. I tuned the number of neighbors (`k`) and selected the best-performing value based on cross-validation.

---

## Model Evaluation

To evaluate model performance, I used the following metrics:
- Confusion Matrix
- Accuracy Score
- F1 Score
- ROC Curve

These helped me understand how well the models were able to distinguish between customers who purchased and those who didn’t.

---

## Clustering

I applied **K-Means clustering** to group customers into different segments based on their age, income, and spending score. I used **PCA (Principal Component Analysis)** to reduce the dimensionality of the data and visualize the clusters in two dimensions. This helped me clearly identify how customers were naturally grouping based on their attributes.

---

## Association Rule Mining

I used the **Apriori algorithm** to discover interesting patterns and associations among different customer attributes. I binned continuous variables into categories like "High Income", "Young", "Low Spending", etc., and generated association rules with a minimum confidence threshold of 0.7.

These rules gave me insights such as how certain age and income groups are associated with specific spending behaviors.

---

## Key Insights

- k-NN, after tuning, outperformed Decision Tree in classification.
- Clustering revealed natural customer segments that can be used for targeted marketing.
- Association rules highlighted behavioral patterns that can be valuable for business strategy.

---

## Real-World Applications

- These classification models could be used for predicting customer purchases.
- Clustering results can help businesses with customer segmentation and personalization.
- Association rules can be used to design effective marketing campaigns or product recommendations.

---

## Challenges Faced

- Initially, balancing between model complexity and overfitting was tricky.
- Converting numerical data into categorical bins for association mining required careful binning.
- Tuning hyperparameters and selecting the right metrics for evaluation needed attention to detail.

---

## Conclusion

This deliverable helped me apply end-to-end machine learning techniques, from preprocessing to evaluation. I gained hands-on experience in building models, tuning them, and deriving actionable insights from data using real-world techniques.
