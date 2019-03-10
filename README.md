# Survival-Analysis-TCGA-Data

The clinical data of three cancer subtypes Breast cancer, Ovarian cancer, and Glioblastoma multiforme was taken from https://portal.gdc.cancer.gov/ with the help of http://bioconductor.org/packages/release/bioc/html/RTCGA.html package in R.

The clinical data was stored in CSV file format and loaded. The clinical data included patietnt's vital status (dead or alive), a times variable that is the days to death or the days followed up and the patient barcode. The disease code was also extracted from the database.

The survival analysis were estimated for all the three cancer subtypes using Kaplan-Meier survival curves. The hazard rates were estimated using Nelson-Aalen for all the three cancer subtypes. Implementation of the Cox proportional hazards regression model and test set was tested using Root Mean Square Error (RMSE).
--  Cox proportional hazards regression: The log-hazard of an individual is a linear function of their static covariates and a population-level baseline hazard that changes over time

The code can be found in this notebook.
