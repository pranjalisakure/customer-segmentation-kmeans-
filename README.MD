\# 🛍️ **Customer Segmentation with K-Means**



\## 📌 **Objective**

Segment retail customers into meaningful groups based on purchase-related features to enable targeted marketing and business insights.



\## 📂 **Dataset**

Mall Customers dataset with the following fields:

\- CustomerID

\- Gender

\- Age

\- Annual Income (k$)

\- Spending Score (1-100)



Source: \[Kaggle – Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)



\## 🧪 **Method**

\- Preprocessing with StandardScaler

\- Elbow method to select the optimal number of clusters

\- K-means clustering

\- Visualization (Income vs Spending; optional PCA 2D)

\- Cluster profiling (means, medians, ranges, counts)



\## 📊 **Results**

\- Clear segment separation and actionable profiles

\- Visuals saved in `/images` folder (elbow curve, cluster scatter)

\- Example clusters:

&nbsp; - High income, high spending → Premium shoppers

&nbsp; - Low income, low spending → Budget-conscious

&nbsp; - High income, low spending → Upsell potential

&nbsp; - Moderate income, high spending → Loyal enthusiasts



\## 🚀 **Repository Structure**

\- `KMeans\_Segmentation.ipynb` → Colab notebook with step-by-step code

\- `images/` → Saved plots

\- `requirements.txt` → Python dependencies

\- `Mall\_Customers.csv` → Dataset (optional)



\## ⚙️ **How to Run**

1\. Install dependencies:

&nbsp;  ```bash

&nbsp;  pip install -r requirements.txt



