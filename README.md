# atope-breast-clustering-analysis
A clustering analysis of the ATOPE+Breast Dataset (https://github.com/salvador-moreno/ATOPE-Breast)

## Files
---
Two jupyter notebooks do the cleaning, preprocessing, and analysis of the ATOPE+Breast dataset.

- **requirements.txt**: requirements for python virtual environment.
- **1.cleaning_and_preprocessing.ipynb**: This notebook does the cleaning and preprocessing of the data. The output are the `demographics-clean.csv` and `records-clean.csv` files(although seeds are fixed, there might be issues with some random processess, hence slightly altering the final results. That is why all data are provided already clean).
- **2.clustering_analysis.ipynb**: This notebook does the clustering analysis. The analysis is preceeded by a more usual analysis by treatment arm. 


## Layered clustering
---
The main results of this analysis are the different layers in which the variables are grouped: HRV, wellness, and normalized wellness. HRV is helpful to assess the physiological status of the patient, how well is she coping with training. 

### HRV
---
![HRV clustering layer](./viz/clustering-l01b-4.png)

### Wellness
---
Wellness and normalized wellness may serve to develop improved adherence strategies depending on their profile.

![Wellness clustering layer](./viz/clustering-l02b-3.png)

![Normalized wellness clustering layer](./viz/clustering-l03a-3.png)

