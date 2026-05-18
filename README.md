# Kaggle Diabetes Dataset Analysis

### Purpose
Analysis of 100k+ patient experiences to find correlations with readmission and outliers in readmission rates

### Data Sources
- Kaggle diabetes dataset
- HHS ICD-9 code crosswalk

### Tools
Python (pandas, matplotlib, seaborn, scipy) · Tableau Public

### Key Findings
- Aftercare NOS has the highest rate of readmission, which can be expected from the high complexity and severity of this broad range of conditions. Psychosis NOS, on the other hand, has the third highest rate of readmission, a result of socioeconomic factors that prevent these patients from receiving the outpatient care they need.
- Diabetes mellitus accounts for the highest volume of admissions but not the highest readmission rate, suggesting that high-frequency conditions aren't necessarily the highest-risk ones for return visits.


### Tableau Dashboard
https://public.tableau.com/views/KaggleDiabetes/Story?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

### Methodology
This project analyzes over 100,000 diabetic patient hospital encounters from the Diabetes 130-US hospitals dataset to identify factors associated with hospital readmissions, particularly 30-day readmissions. Using Python, Pandas, NumPy, Seaborn, and Tableau, the dataset was cleaned and standardized by handling missing values, removing highly incomplete variables such as weight, consolidating ICD-9 diagnosis codes, and merging diagnosis descriptions through an ICD-9 crosswalk table. Exploratory data analysis focused on demographic characteristics, hospital utilization metrics, diagnoses, laboratory testing, and medication patterns across readmission groups.

Additional analysis was performed on patients with a primary diagnosis of diabetes mellitus to examine HbA1c testing, insulin usage, medication changes, and secondary diagnoses associated with readmission. Statistical testing was used to evaluate differences in HbA1c testing rates between diabetic patients and those readmitted within 30 days. The cleaned datasets were then exported to Tableau to create interactive dashboards and story points highlighting readmission trends, utilization patterns, and clinical risk factors.
