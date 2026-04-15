# Earthquake Clustering Machine Learning

## Project Description
This repository contains a machine learning project aimed at clustering earthquake data to uncover patterns and insights that can lead to better understanding and prediction of seismic activities. By applying various clustering algorithms, the project analyzes geographical and temporal data of earthquakes, providing a foundation for further research in earthquake prediction and risk assessment.

## Methodology
1. **Data Collection**: The project uses publicly available earthquake data from sources such as the USGS and other geological survey organizations.
2. **Data Preprocessing**: Clean and preprocess the collected data, including normalization and handling missing values. Convert data into a suitable format for analysis.
3. **Exploratory Data Analysis (EDA)**: Conduct EDA to visualize and understand the characteristics of the data. This includes generating plots and statistics that highlight important features of the dataset.
4. **Clustering Algorithms**: Implement various clustering algorithms such as:
   - K-Means Clustering
   - DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
   - Hierarchical Clustering
5. **Model Evaluation**: Evaluate the performance of the clustering models using metrics like Silhouette Score and Davies-Bouldin Index to determine the optimal number of clusters and the effectiveness of the chosen algorithms.
6. **Visualization**: Create visual representations of the clustered data to facilitate understanding and interpretation of the results, including 2D and 3D plots.
7. **Insights and Conclusions**: Summarize key findings and insights from the clustering results, discussing their implications in earthquake monitoring and prediction.

## Usage Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/sandipbhandari1/Earthquake_Clustering_Machine_Learning.git
   cd Earthquake_Clustering_Machine_Learning
   ```
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   Execute the main script to start the analysis:
   ```bash
   python main.py
   ```
4. Review the results:
   After execution, results will be saved in the `results` directory. Check visualizations and summaries in the specified output files.

## Contributing
Contributions to enhance the project are welcome. Please fork the repository and create a pull request with your proposed changes. Before contributing, ensure that you've followed the project's coding standards and included relevant tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or issues, please reach out to [sandipbhandari1](https://github.com/sandipbhandari1) on GitHub.