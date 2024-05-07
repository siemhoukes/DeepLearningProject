# DeepLearningProject
This repository contains the code, data and analysis used in group 10's Deep Learning Project, based on Neural Collaborative Filtering (NCF).

To replicate this study and ensure accurate reproduction of the results, it is essential to follow the methodology detailed across three Python notebooks. The steps for each notebook are outlined as follows:

1. Descriptive Statistics Notebook
Visualizations: Utilize this notebook to produce descriptive graphs and visualizations that provide insights into the characteristics of the dataset.
Analysis: Include statistical analyses of the preprocessed data to understand key patterns and trends.

2. Preprocessing Notebook
Data Setup: Start with the raw data in CSV format. Ensure all necessary files are available and properly formatted.
Run the Notebook: Execute the preprocessing steps sequentially from top to bottom to:
Clean the data by removing redundant columns and handling missing values.
Engineer extra features by encoding and flagging important variables.
Generate negative instances according to the sampling strategy described. This step may be time-intensive as it involves iterating over the dataset multiple times.
Output: Save the processed data as a CSV file for use in subsequent notebooks.

3. Model Notebook
Load Processed Data: Import the preprocessed data for model training.
Data Preparation: Implement Word2Vec embeddings and normalize or encode all features to ensure compatibility with the model architecture.
Output: Generate evaluation plots and print performance metrics.
