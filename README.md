# Clustering_Data
these is the project for clustering the non behavioural data and implementation of statistical Data visualisation

# Data Clustering and Feature Importance

This Python script focuses on data clustering and feature importance analysis using the K-Means algorithm and t-Distributed Stochastic Neighbor Embedding (t-SNE). The dataset used is related to pet owner behavior and attributes.

## Prerequisites

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly

## Installation

1. Install the required packages:

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn plotly
    ```

2. Clone the repository:

    ```bash
    git clone https://github.com/your-username/data-clustering-feature-importance.git
    cd data-clustering-feature-importance
    ```

## Usage

1. Prepare your dataset in an Excel file (e.g., `PathOfFile.xlsx`) with relevant columns.

2. Update the script to point to your dataset:

    ```python
    df = pd.read_excel(r'C:\Users\PathOfFile.xlsx', sheet_name='cbarq-pet-owner-data-corrected')
    ```

3. Run the script:

    ```bash
    python data_clustering_feature_importance.py
    ```

4. View the output which includes labeled data (`Labeled_Non_Behavioural_data.csv`) and a scatter plot (`digits_tsne-generated_{k}_cluster.png`) representing the K-Means clustering.

## Output

The script outputs labeled data (`Labeled_Non_Behavioural_data.csv`) and a scatter plot (`digits_tsne-generated_{k}_cluster.png`) representing the K-Means clustering.

## Customization

- Adjust the number of clusters (`k`) in the script based on your dataset characteristics.
- Customize the script for your specific dataset columns and preprocessing steps.

## Notes

- K-Means clustering is used to group similar data points.
- t-SNE is employed for dimensionality reduction and visualization of high-dimensional data.
