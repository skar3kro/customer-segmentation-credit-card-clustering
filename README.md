# 🧮 Customer Segmentation using Clustering

This project performs **unsupervised customer segmentation** on a credit card dataset using **PCA + K-Means**.  
The goal is to identify distinct customer profiles to help financial institutions target retention and engagement strategies effectively.

---

## 📘 Dataset
- Source: [Kaggle - Credit Card Customers Dataset](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)
- Size: ~10,000 records, 21 features

---

## ⚙️ Methods Used
- Exploratory Data Analysis (EDA)
- Feature Encoding (One-Hot + Ordinal)
- Standardization (Z-score)
- Principal Component Analysis (PCA)
- K-Means Clustering (Elbow + Silhouette)
- Validation (Cluster Stability + Attrition Mapping)

---

## 🧠 Results
| Cluster | Size | Churn Rate (%) | Key Traits |
|:--------:|:-----:|:---------------:|:------------|
| **0** | 2,719 | 15.5% | High credit limit, high spending, premium users |
| **1** | 7,408 | 16.3% | Low activity, higher utilization, potential churners |

---

## 💡 Insights
- Cluster 0 → **Engaged customers** — reward & loyalty programs recommended  
- Cluster 1 → **At-risk customers** — focus on re-engagement and offers  

---

## 🛠️ Tools & Libraries
- Python 3.10  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn  

---

## 📈 Next Steps
- Compare results with **DBSCAN** and **GMM**  
- Incorporate **time-based trends**  
- Extend project into a **churn prediction model**

---

## 👨‍💻 Author
**Saikat Choudhury**  
_Data Science Enthusiast | Financial Markets Learner | Exploring ML for Business Insights_
