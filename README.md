# 💳 Credit Card Customer Segmentation using Unsupervised Machine Learning

> An end-to-end Unsupervised Machine Learning project that segments credit card customers based on their spending behavior and financial characteristics to support targeted marketing strategies and customer relationship management.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-success)
![Clustering](https://img.shields.io/badge/Model-K--Means-orange)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)

---

# 🚀 Repository Highlights

- End-to-End Unsupervised Machine Learning Pipeline
- Customer Segmentation using Clustering
- Exploratory Data Analysis (EDA)
- Data Preprocessing & Feature Scaling
- K-Means & Hierarchical Clustering
- PCA for Cluster Visualization
- Cluster Evaluation using Silhouette Score & Cophenetic Correlation
- Actionable Business Recommendations

---

# 📌 Business Problem

Financial institutions manage customers with diverse spending patterns, credit utilization, and repayment behavior. Treating all customers identically often results in ineffective marketing campaigns and lower customer engagement.

This project applies unsupervised machine learning techniques to identify meaningful customer segments, enabling personalized marketing, improved customer retention, and data-driven business decision-making.

---

# 🎯 Project Objective

The primary objective of this project is to:

- Identify distinct customer segments using clustering techniques.
- Compare multiple clustering approaches.
- Determine the optimal number of customer groups.
- Generate business insights for targeted marketing and customer relationship management.

---

# 📊 Dataset Overview

The dataset contains information for **660 credit card customers**, including demographic and financial attributes used for segmentation. :contentReference[oaicite:1]{index=1}

The project analyzes customer characteristics such as:

- Credit Limit
- Number of Credit Cards
- Bank Visits
- Online Visits
- Calls Made
- Spending Behaviour
- Other customer-related financial attributes

---

# 🔄 Machine Learning Workflow

```text
Business Understanding
        │
        ▼
Data Collection
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Feature Scaling
        │
        ▼
Dimensionality Reduction (PCA)
        │
        ▼
K-Means Clustering
        │
        ▼
Hierarchical Clustering
        │
        ▼
Cluster Evaluation
        │
        ▼
Business Insights & Recommendations
```

---

# 📈 Exploratory Data Analysis

The exploratory data analysis focused on understanding customer characteristics before clustering.

Key activities included:

- Distribution analysis
- Outlier detection
- Correlation analysis
- Pairwise relationship analysis
- Customer behavior exploration

The analysis revealed meaningful variations across customers, supporting the need for segmentation.

---

# 🛠 Data Preprocessing

The following preprocessing techniques were applied:

- Missing value verification
- Duplicate value check
- Outlier assessment
- Feature Scaling using StandardScaler
- Data preparation for clustering algorithms

---

# 🤖 Model Development

Two clustering approaches were implemented and compared.

### K-Means Clustering

- Elbow Method
- Silhouette Analysis
- Optimal cluster selection

### Hierarchical Clustering

- Agglomerative clustering
- Dendrogram analysis
- Cophenetic Correlation evaluation

Principal Component Analysis (PCA) was also used to visualize customer clusters in two dimensions.

---

# 📏 Model Evaluation

The clustering solutions were evaluated using:

- Silhouette Score
- Cophenetic Correlation Coefficient
- Cluster Separation
- Cluster Interpretability

The selected clustering solution demonstrated meaningful separation between customer groups while maintaining business interpretability.

---

# 💡 Key Business Insights

The analysis identified distinct customer segments with different financial and behavioral characteristics.

These insights can help organizations:

- Design personalized marketing campaigns
- Improve customer retention
- Identify high-value customers
- Optimize cross-selling and up-selling strategies
- Enhance customer relationship management

---

# 🧰 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

### Machine Learning Techniques

- K-Means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- StandardScaler
- Silhouette Analysis
- Cophenetic Correlation

---

# 📂 Repository Structure

```text
credit-card-customer-segmentation/

├── README.md
├── Credit Card Customer Data.xlsx
├── Business Report.pdf
└── Unsupervised_Learning_Project_CreditCard....ipynb
```

---

# 📌 Conclusion

This project demonstrates an end-to-end unsupervised machine learning workflow for customer segmentation. By combining exploratory data analysis, feature scaling, clustering techniques, dimensionality reduction, and cluster evaluation, the project identifies meaningful customer groups that can support targeted marketing, improve customer engagement, and enable data-driven business decisions.

---

## 👨‍💻 Author

**Akshay Hande**

Data Scientist | Machine Learning | Artificial Intelligence

---
