
---

# 🔹 **TASK 2 – README (Customer Segmentation)**

```markdown
# 👥 Customer Segmentation using K-Means

It focuses on clustering customers based on behavior and spending patterns.

---

## 📌 Objective
Group customers into meaningful segments using unsupervised learning.

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🔍 Workflow

### 1. Data Cleaning
- Handled missing values in `Income`
- Removed unrealistic records
- Standardized categorical values (Marital Status, Education)

### 2. Feature Engineering
Created new features:
- `Age`
- `Total_Spending`
- `Total_Purchases`
- `Customer_Tenure`
- `Children`

Dropped irrelevant/redundant columns

---

### 3. Data Transformation
- Label Encoding for categorical variables
- Standardization using StandardScaler

---

### 4. Clustering
- Used **K-Means**
- Determined optimal clusters using:
  - Elbow Method
  - Silhouette Score

---

### 5. Visualization
- PCA (2D visualization)
- Cluster-wise comparison:
  - Spending behavior
  - Income distribution

---

## 📊 Output
- Customers grouped into clusters
- Behavioral insights per cluster

---

## 📌 Learnings
- Difference between supervised vs unsupervised learning
- Importance of scaling before clustering
- Interpreting clusters using domain understanding

---

