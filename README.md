# Customer-Segmentation-Using-KMeans
Customer Segmentation Using KMeans, Data Visualization and comparision with DBScan
Customer Segmentation Using KMeans
In the fast-paced retail industry, understanding customer behavior is key to effective marketing and product development. This project leverages customer segmentation through clustering, a machine learning technique that groups similar customers together based on their attributes.

Overview
The dataset used in this project is sourced from Kaggle and includes customer details such as age, annual income, and a spending score, which reflects customer behavior and spending habits. The main steps involved in this project are:

Exploratory Data Analysis (EDA)
Data Preprocessing
Clustering
Cluster Interpretation and Visualization
We utilized the KMeans algorithm for clustering, validated by the silhouette score, to identify distinct customer segments. The results were visualized to provide actionable insights for targeted marketing and product development.

Data
The dataset is loaded from a CSV file and contains the following columns:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100)

Steps
Exploratory Data Analysis (EDA): Examined the structure and characteristics of the dataset, including data shape, types, and missing values.

Data Preprocessing: Scaled features to ensure equal weight in clustering. This is a crucial step before applying KMeans.

Clustering: Applied KMeans algorithm to group customers into clusters. The optimal number of clusters was determined using the silhouette score.

Cluster Interpretation and Visualization: Interpreted the clusters by analyzing average feature values and visualized clusters using scatter plots.

Clusters
Cluster 0: "Conservative Middle-Aged" - Middle-aged individuals with low income and low spending score. Less responsive to marketing efforts.
Cluster 1: "Young High Earners" - Young individuals with high income and high spending score. Potential key target for marketing campaigns.
Cluster 2: "Balanced Middle-Aged" - Middle-aged individuals with moderate income and balanced spending. Focus on value and quality in marketing.
Cluster 3: "Wealthy Savers" - High income, low spending score. Potential insights into saving behavior or dissatisfaction with offerings.
Cluster 4: "Young Spenders" - Young individuals with low income but high spending score. Might prioritize experiences over saving.
Conclusion
This project demonstrates the utility of customer segmentation using KMeans clustering. The insights gained can drive targeted marketing efforts and inform product development. Future work could expand this analysis by incorporating additional features or exploring alternative clustering algorithms.
