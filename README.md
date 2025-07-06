**Netflix Clustering Project**
This project analyzes data from the Netflix catalog and applies machine learning techniques to cluster content based on features such as genre, duration, and type (Movie or TV Show).

**Description**
The workflow includes:

Data cleaning and preprocessing

Feature selection: type, listed_in, duration

Categorical encoding using MultiLabelBinarizer

Data normalization using StandardScaler

Clustering with K-Means

Visualization of clusters using PCA (Principal Component Analysis)

Technologies Used
pandas

scikit-learn

matplotlib

**How to Run**
Make sure the Netflix.csv file is in the same directory as the notebook.

Open and run the Netflix.ipynb notebook to process the data and view clustering results.

**Output**
The notebook produces a scatter plot that visually represents how Netflix content is grouped into clusters. This can reveal patterns such as common genres, typical durations, and trends in TV vs Movie offerings.

