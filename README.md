🍿 Netflix Show & Movie Clustering Project 🎬
This repository contains the code and resources for a machine learning project that explores and clusters Netflix shows and movies based on their content, ultimately providing an interactive dashboard for content discovery.

🌟 Project Overview
Have you ever wondered how Netflix groups its vast library of content to recommend your next binge-watch? This project attempts to answer that question by applying unsupervised machine learning techniques to a dataset of Netflix titles. The goal is to identify inherent patterns within the content and group similar shows and movies into distinct clusters.

A key deliverable of this project is an interactive Gradio dashboard that allows users to input a Netflix title and instantly discover which content cluster it belongs to, along with other similar titles within that same cluster.

✨ Features
Data Preprocessing: Cleans and prepares raw Netflix dataset.

Feature Engineering: Combines and transforms textual features (title, description, genres, cast, director, etc.) into a numerical format suitable for machine learning.

Dimensionality Reduction: Uses TruncatedSVD to reduce the high dimensionality of the text features, improving efficiency and interpretability.

K-Means Clustering: Groups Netflix shows and movies into k (optimal number determined through analysis) distinct clusters based on their content similarity.

Cluster Analysis & Interpretation: Examines the characteristics of each cluster to understand the types of content within them.

Interactive Dashboard: A Gradio-based web interface for exploring content clusters by inputting a show/movie title.

🚀 Technologies Used
Python 3.x

pandas: For data manipulation and analysis.

scikit-learn: For machine learning algorithms (TF-IDF, TruncatedSVD, KMeans).

nltk: For natural language processing tasks (stopwords, text cleaning).

umap-learn: For advanced dimensionality reduction and visualization of clusters.

matplotlib & seaborn: For data visualization (e.g., Elbow Method, Silhouette Score, UMAP plots).

wordcloud: For generating word clouds to visualize prominent terms in clusters.

joblib: For saving and loading trained machine learning models.

gradio: For building the interactive web dashboard.
