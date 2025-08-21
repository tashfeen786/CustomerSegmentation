# CustomerSegmentation

#  Mall Customers Clustering

## 📌 Project Overview

This project applies **unsupervised learning** techniques to segment mall customers into meaningful groups based on their **annual income, spending score, age, and gender**.

The aim is to help businesses **understand customer behavior**, identify **high-value customers**, and design **targeted marketing strategies**.

---

##  Dataset

- **Source**: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)
- **Features**:
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🔧 Tools & Libraries

- **Python** 🐍
- **Pandas, NumPy** → Data handling
- **Matplotlib** → Data visualization
- **Scikit-learn** → Clustering (K-Means, DBSCAN), Preprocessing, PCA

---

## 📊 Steps Covered

1. **Data Preprocessing**

   - Handle missing values
   - Scale numerical features
   - Encode categorical features (Gender)

2. **Clustering (K-Means)**

   - Elbow Method to choose optimal K
   - Silhouette Score evaluation
   - Final clustering with K-Means

3. **Visualization**

   - 2D plot: **Annual Income vs Spending Score**
   - PCA (2D projection of all features)

4. **Cluster Analysis**

   - Cluster summary (average age, income, spending)
   - Average spending per cluster

5. **Bonus: DBSCAN**
   - Density-based clustering to detect non-spherical clusters and outliers

---

## 📸 Sample Visualizations

- **Elbow Method & Silhouette Score**
- **Clusters (Income vs Spending)**
- **Clusters (PCA 2D projection)**
- **DBSCAN clusters with noise points**

---

## 📈 Results & Insights

- Customers can be grouped into **distinct segments** such as:

  - 💎 **High Income, High Spending** → Premium customers
  - 🛒 **Low Income, High Spending** → Impulsive spenders
  - 📉 **High Income, Low Spending** → Potential but low engagement
  - 👨‍👩‍👧 **Middle class families** → Moderate income, moderate spending

- Business can use these clusters for **targeted marketing campaigns**.

---

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/tashfeen786/mall-customers-clustering.git
   cd mall-customers-clustering
   ```

Future Work

Try Hierarchical Clustering

Use advanced visualization (Seaborn, Plotly)

Deploy interactive dashboard with Streamlit

👤 Author

Tashfeen Aziz

📌 Data Analyst | Python Developer | ML/DL Enthusiast

🌐 LinkedIn: https://www.linkedin.com/in/tashfeen-aziz-b51361292/
| GitHub: https://github.com/tashfeen786 
