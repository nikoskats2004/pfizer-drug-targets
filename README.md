# Pfizer Drug-Target Interaction Datasets

## Author
- Nikolaos Katsikavalis 

## Project Overview
This repository contains the data collected and prepared for network analysis regarding **Pfizer drugs and their target genes/proteins**. 

The data was gathered and cross-referenced from multiple biomedical databases:
* **DrugBank & PubChem:** For drug profiles and verified interactions.
* **SwissTargetPrediction & GeneCards:** For protein target predictions and gene information.

## File Descriptions
These files are formatted as clean CSV tables, ready to be imported directly into network visualization tools like **Cytoscape**:
* `PFIZER.xlsx - SYNOLO.csv`: The complete consolidated network dataset containing all interactions.
* `PFIZER.xlsx - common.csv`: Filtered data highlighting the shared biological targets within the network.
* Remaining CSV files: Source data extracted from each individual database.
