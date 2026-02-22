# GeoSpatial-Hw1
CSCI 587 Homework 1 
Requirements
Python 3.6 or higher. All code is implemented in a Google Colab notebook. The following libraries are used:

numpy
pandas
matplotlib
time
random
collections

All libraries are pre-installed in Google Colab and require no additional installation.

Dataset:
The dataset used is a CSV file of Points of Interest (POIs) downloaded from OpenStreetMap via Overpass Turbo. The file should be named interpreter.csv before running the notebook.

How to Run:
Open Google Colab at https://colab.research.google.com
Ensure the runtime is connected by clicking the Connect button in the top right corner
Upload the notebook file GeoHw_1.ipynb
Upload the dataset file interpreter.csv when prompted by the file upload cell
Run all cells in order from top to bottom using Runtime → Run All
All plots will be generated and saved automatically as PNG files


Output Files
The following files are automatically generated when the notebook is run:

poi_data_clean.csv — cleaned dataset saved after preprocessing
knn_linear_search_performance.png
range_query_linear_search_performance.png
knn_performance_story.png
range_query_performance_story

