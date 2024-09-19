# Airline-Safety-Clustering-Project
Implemented agglomerative and divisive clustering to group airlines based on safety records from 1985–2014, using incidents, fatal accidents, and fatalities data. Visualized and compared clustering results to assess patterns in airline safety
# Problem Statement
This project aims to analyze whether travelers should avoid airlines that have experienced crashes in the past. Using data from the Aviation Safety Network, the goal is to identify clusters of airlines with similar safety records, using two different clustering approaches: agglomerative and divisive. The comparison of these approaches will help us understand how airlines group based on their safety records.
The dataset for this has been sourced from Aviation Safety Network and is available at this link: https://www.kaggle.com/fivethirtyeight/fivethirtyeight-airline-safety-dataset.Links to an external site.
![Screenshot 2024-09-18 at 5 31 26 PM](https://github.com/user-attachments/assets/e3dc78e6-fbd1-4d49-b86b-4a0c2acde58f)
# Instructions
Step 1: Clustering
Two clustering methods are applied:
Agglomerative Clustering: This is a bottom-up approach where each data point starts in its own cluster, and clusters are merged iteratively.
Divisive Clustering: A top-down approach where all points start in a single cluster, and clusters are divided iteratively.
Step 2: Comparing Results
The two clustering approaches are compared to see if they lead to similar or different results. Appropriate visualizations and interpretations are provided to show the results and explain the differences.
# Methodology
# Data Preprocessing:
Clean the dataset.
Normalize the data, if required, to ensure appropriate clustering.
# Clustering:
Implement Agglomerative Clustering using the sklearn library.
Implement Divisive Clustering using techniques such as divisive hierarchical clustering.
# Visualization:
Generate dendrograms for the hierarchical approaches.
Plot clusters using scatter plots, colored by cluster labels.
![image](https://github.com/user-attachments/assets/80a77908-673a-43c1-afee-c5e61786d360)
![image](https://github.com/user-attachments/assets/69f50ceb-82bf-4f6c-807d-02486bb046ab)
# Evaluation:
Compare the clustering results to identify patterns.
Interpret the airline clusters based on safety records and see if there is a correlation between past crashes and cluster membership.
# Dependencies
Python 3.x|Pandas|NumPy|Scikit-learn|Matplotlib|Seaborn|Scipy

Usage
Download the dataset from Kaggle.
Preprocess the data by removing any irrelevant columns.
Run the script to perform clustering using agglomerative and divisive methods.
Compare the clustering results and generate visualizations for interpretation.
# Conclusion
This project helps determine if clustering airlines based on past incidents and accidents yields insights into their safety records. Both agglomerative and divisive clustering techniques are useful for identifying patterns in airline safety, and this project evaluates how closely the results align between these two methods.


