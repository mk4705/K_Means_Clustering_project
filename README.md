K-Means Clustering Project: College Data

Overview
This project demonstrates unsupervised learning using K-Means clustering on the College_Data dataset. The goal is to group U.S. colleges and universities based on their institutional characteristics — without using the “Private/Public” label—revealing underlying structure in the data and visualizing patterns between institutions.

Main Steps in the Notebook

Data Loading & Cleaning:
The notebook loads and explores the data, examining numeric summaries and handling categorical variables.

Exploratory Data Analysis:
Visualizations (using Seaborn and Matplotlib) highlight relationships between key variables (e.g., tuition, enrollment, graduation rate, faculty ratio).

K-Means Clustering:
K-Means with k=2 is applied to cluster colleges, aiming to rediscover the hidden “Private/Public” split solely based on features.

Standard scaler or normalization may be applied for fair distance measurement.
The model is trained on all features except the “Private” column.
The output assigns a cluster number (0 or 1) to each college.

Results & Evaluation:
Cluster assignments are compared with the true “Private” labels.
A confusion matrix and classification report are generated, indicating how well clustering aligns with the known public/private split.

Visualization:
Cluster results are visualized using scatter plots (e.g., Outstate Tuition vs. Grad Rate, colored by cluster or true label).
Insights about cluster characteristics are discussed.
