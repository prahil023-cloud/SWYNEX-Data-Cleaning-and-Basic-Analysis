Final Bioinformatics Report

Title

Basic Analysis and Visualization of GSE2034 Gene Expression Data

1. Introduction

For this project, I worked with the GSE2034 gene expression dataset from the NCBI Gene Expression Omnibus (GEO).

The dataset is related to breast cancer relapse-free survival. It contains 286 samples and 22,283 probe rows.

The main purpose of this project was to check the quality of the data, perform basic analysis and understand the gene expression values using simple graphs.

2. Research Question

Can basic data cleaning and visualization help us understand the distribution of gene expression values in the GSE2034 dataset?

3. Dataset

The dataset used in this project was:

- GEO Accession: GSE2034
- Organism: Homo sapiens
- Number of samples: 286
- Number of probes: 22,283
- Data type: Gene expression data

The dataset was obtained from the NCBI GEO database.

4. Tools Used

The following tools were used for this work:

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

5. Data Cleaning

Before doing the analysis, I checked the dataset for some common data quality problems.

The following checks were performed:

- Missing values
- Duplicate probe IDs
- Negative expression values

The results were:

Check| Result
Missing values| 0
Duplicate probe IDs| 0
Negative expression values| 0

No missing values, duplicate probe IDs or negative expression values were found in the checks performed.

6. Basic Analysis

After the data cleaning step, basic descriptive statistics were calculated.

The analysis included:

- Minimum expression value
- Maximum expression value
- Mean expression value
- Median expression value

These values were used to get a basic idea about the expression data and its distribution.

7. Data Visualization

Two graphs were created during the analysis.

Graph 1: Distribution of Mean Expression

The first graph shows the distribution of mean expression values.

This graph helps in understanding how the average expression values are distributed in the dataset.

Graph 2: Distribution of Median Expression

The second graph shows the distribution of median expression values.

This gives another view of the expression data and helps in understanding its central distribution.

Both graphs were created using Matplotlib in Python.

8. Results

The data quality checks did not show missing values, duplicate probe IDs or negative expression values.

The descriptive analysis gave the minimum, maximum, mean and median expression values.

The two graphs helped to visually understand the distribution of mean and median expression values in the dataset.

9. Discussion

From this basic analysis, the dataset could be checked and explored without performing advanced statistical analysis.

The mean and median values give useful information about the general distribution of the expression data.

However, these results alone cannot tell us which genes are related to breast cancer relapse. More detailed analysis would be needed for that purpose.

10. Limitations

This project was limited to basic data cleaning, descriptive statistics and visualization.

The following analyses were not performed:

- Differential gene expression analysis
- Statistical hypothesis testing
- Survival analysis
- Machine learning
- Pathway analysis

Therefore, the results should be considered as a basic exploratory analysis of the dataset.

11. Conclusion

In this project, I worked with the GSE2034 gene expression dataset and performed basic data cleaning and analysis.

I checked the dataset for missing values, duplicate probe IDs and negative expression values. I also calculated basic descriptive statistics and created graphs for mean and median expression values.

This project helped me understand the basic steps involved in handling and visualizing a biological dataset using Python.

12. References

1. NCBI Gene Expression Omnibus (GEO) – GSE2034.
2. Python documentation.
3. Pandas documentation.
4. Matplotlib documentation.
