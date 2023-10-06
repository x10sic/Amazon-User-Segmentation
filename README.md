# Amazon-User-Segmentation
Project Title: Amazon User Segmentation with K-means Clustering

Description:

Everyone have unique homepage in amazon.com because they uses their last/previous data to next how your homepage visible. This project aims to analyze Amazon user data and segment customers into distinct groups using the powerful K-means clustering algorithm. By identifying common purchasing behaviors and preferences among users, this segmentation enables targeted marketing strategies and personalized recommendations, ultimately enhancing the user experience.

Key Features:

Utilized K-means Clustering: Employed the K-means algorithm for customer segmentation based on purchase history and preferences.

Interactive Charts: Visualized the results using interactive charts and graphs to provide valuable insights into user segments.

Google Colab IDE: Developed and implemented the project in Google Colab, taking advantage of its collaborative and computational capabilities.

Technologies Used:

Python
Google Colab
K-means Clustering
Data Visualization (e.g., Matplotlib, Seaborn)

#Steps used : 

Step 1:- we need to decide no of clusters k, for this we have a formula WCSS(defined as the sum of the square distance between each memberif cluster and its centroid)
        and plotting this we will get a graph and the following elbow method we find the optimal K(clusters).
Step 2:-At random points select K the centroids(may not be from your dataset)
Step 3:- Assign data point to the closest centroid.
Step 4:- Place the new centroid of each cluster after completing
Step 5:-Reassign each data point to the new closest centroid if any reassignment took place go to step 4 otherwise go to FIN
then your model is ready 
Based on this algorithm we have designed the project.

Results:
In this project we took Annual income and ratings as parameters for clustering if you want you would take more parameters for clustering..
And also this algorithm works for searching too. 
The project successfully grouped Amazon users into distinct segments, allowing for more effective marketing strategies and personalized recommendations. These insights can potentially lead to increased customer satisfaction and revenue.

Note: Please ensure that sensitive or private data is handled appropriately and that you comply with all privacy and data protection regulations when working with user data.

Project Structure:

data/: Contains the dataset used for segmentation.
notebooks/: Google Colab notebooks for data preprocessing, K-means clustering, and visualization.
charts/: Generated charts and visualizations.
Feel free to explore the code and results in the respective directories.

Usage:

Clone the repository.
Open the Google Colab notebooks to explore the analysis and segmentation process.
Review the visualizations in the charts/ directory to gain insights.
