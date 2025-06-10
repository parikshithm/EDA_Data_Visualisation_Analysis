Car MSRP Data Analysis - Initial Load and Inspection
This repository contains a Google Colab notebook (.ipynb file) for the initial loading and inspection of a car dataset, specifically focusing on MSRP (Manufacturer's Suggested Retail Price) data.

Project Overview
This notebook addresses the first step of a data analysis project: loading the data, examining its metadata and versions, and acknowledging the data source. It sets up the environment by importing necessary libraries and loading an Excel file into a Pandas DataFrame.

Getting Started
To run this notebook, you'll need access to Google Colab and a Kaggle API key (if the data is sourced from Kaggle and requires authentication).

Prerequisites

Google Account: Required to access Google Colab.
Kaggle Account and API Key: If MSRP_unstructured.xlsx is a Kaggle dataset, you'll need to set up your Kaggle API credentials. Follow the instructions here to generate your KAGGLE_USERNAME and KAGGLE_KEY. These should be stored as user data secrets in your Colab environment for security (as shown in the notebook).
Installation (within Google Colab)

The notebook handles library imports. No separate installation steps are needed if running within Google Colab, as the primary libraries (NumPy, Pandas, Matplotlib, Seaborn) are pre-installed.

Usage

Open in Google Colab: Click the "Open in Colab" badge (if you add one, see below) or upload the .ipynb file to your Google Drive and open it with Google Colab.
Set up Kaggle Credentials (if applicable):
In Colab, go to Secrets (usually a key icon on the left sidebar).
Add new secrets named KAGGLE_USERNAME and KAGGLE_KEY with your respective Kaggle credentials.
Upload the Dataset: Ensure the MSRP_unstructured.xlsx file is uploaded to your Google Colab environment or mounted from Google Drive so the notebook can access it.
Run Cells: Execute each cell sequentially. The notebook will:
Import necessary libraries.
Print the versions of the imported libraries (Pandas, NumPy, Matplotlib, Seaborn).
Load the MSRP_unstructured.xlsx file into a Pandas DataFrame.
Display the first 14 rows of the DataFrame to verify data loading.
Notebook Contents
The notebook is structured with the following key sections:

Q1) Load the data, reflect the meta data, the versions, acknowledge the source of data
a. Import the necessary libraries: Imports numpy, pandas, matplotlib, and seaborn.
b. Print the versions of the libraries: Outputs the versions of the imported libraries.
c. Open the data file in Colab (not on local systems) and d. Create a dataframe from the given dataset: Loads MSRP_unstructured.xlsx into a Pandas DataFrame.
e. Check whether the data is loaded as per expectations in the last few rows: Displays the head of the DataFrame to confirm successful loading and initial structure.
Data Source
The data used in this notebook is sourced from an Excel file named MSRP_unstructured.xlsx. Please acknowledge the original source of this data if it's publicly available (e.g., Kaggle, UCI Machine Learning Repository, etc.).

(Replace this placeholder with the actual data source if known. For example: "The dataset MSRP_unstructured.xlsx is a publicly available dataset from Kaggle, titled 'Car Features and MSRP'." with a link to the Kaggle page.)

Contributing
Feel free to fork this repository and contribute to the analysis of this dataset!
