# Impact of PM2.5 on Pediatric Respiratory Healthcare Utilization

This repository contains the data preparation and statistical analysis codes used in the study: 
"The Impact of PM2.5 Exposure on Pediatric Respiratory Diseases and Healthcare Utilization: A Retrospective Cohort Study Based on the National Infant Health Checkup"

# Data Availability Statement
The raw data used in this study (National Health Insurance Service Cohort) are legally restricted from public sharing to protect personal information. These raw datasets can only be accessed and analyzed offline at the designated NHIS Big Data Centers by approved researchers. 

However, to ensure full transparency and reproducibility, we provide the complete, reproducible data preparation and analysis codes below. Approved researchers can replicate our findings by running these scripts within the secure NHIS offline server environment.

# File Structure
* `01_Data_Preparation.sas`: Main data construction for pediatric respiratory outcomes.
* `02_Main_Analysis.do`: Main IV-Fixed Effects panel regressions for respiratory diseases.
* `03_Robustness_Data_Prep.sas`: Negative control data extraction (Surgery & Burns).
* `04_Robustness_Analysis.do`: Falsification tests (Surgery & Burns) and Subgroup analyses (COVID-19 Era, High PM2.5 Exposure, Gender).

# System Requirements
* Data Preparation: SAS 9.4 or higher
* Statistical Analysis: Stata 16.0 or higher (requires `xtivreg2` package)
