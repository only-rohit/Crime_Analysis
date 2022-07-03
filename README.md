# Criminal-Activity-Hotspots

### The Problem Statement
To facilitate effective distribution of police forces in a city among multiple districts based on the extent to which each district is prone to crime at a given hour, in a given day, for a given month.

### MODEL EVALUATION METRICS
We have evaluated our models based on the following metrics that are common to most ML problems :
- Accuracy
- Precision
- Recall
- F1 Score
- Unweighted Average Recall

### Testing Samples
Sample 1 : 25% of crimeData (With class imbalance)
Sample 2 : 25% of crimeData (Without class imbalance - Achieved by oversampling)
Sample 3 : All crime records from 2012-2014

### Repository Structure
The repository has been structured to help in easy comprehension of my work as it will help anybody who wishes to reproduce this work do so with relative ease.  

* data
* notebooks
  - main_nb.ipynb
* results
  - plots
* utils
  - util_script.py
* README

**data :** Contains all the necessary data files used  
**notebooks :** Jupyter notebooks used  
**results :** Includes only the .png plots generated as of now (will be updated later)  
**utils :** Utility Script folder written for simplifying routine tasks  
