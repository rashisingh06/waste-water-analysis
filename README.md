# waste-water-analysis

**Project Summary Report: 2014 Environmental Performance Index (EPI) - Wastewater Treatment Analysis**

**Data Set Information**:

_Title_: 2014 Environmental Performance Index (EPI)
_Time Series Indicator Data_: January 2014
_Data Set URL_: EPI 2014 Data | SEDAC Data
_Data Set Citation_:
Yale Center for Environmental Law and Policy (YCELP), Yale University
Center for International Earth Science Information Network (CIESIN), Columbia University
World Economic Forum (WEF)
DOI: http://dx.doi.org/10.7927/H4416V05
Accessed: DAY MONTH YEAR

**Project Overview**:
The analysis focuses on the Wastewater Treatment indicator from the 2014 Environmental Performance Index (EPI). The dataset contains information on the percentage of anthropogenic wastewater that receives treatment (%), sourced from Malik, O. (2013), the Global Database of National Wastewater Treatment. Not Applicable (NA) values may be present in the dataset.

**Key Findings**:

**Initial Data Exploration**:

The dataset was extracted from the 2014 EPI time series indicator data.
An initial exploration was conducted to understand the structure and contents of the data.

**Country-Region Mapping:**

A mapping of countries to their respective regions was performed to enhance the geographical context of the analysis.

**Data Cleaning**:

Missing values (NA) were identified and handled appropriately to ensure data integrity.
The cleaned dataset, wastewater_data_clean, was used for subsequent analyses.

**Clustering Analysis**:

The data was subjected to k-means clustering based on the percentage of wastewater treated.
Four clusters were identified to group countries based on their wastewater treatment percentages.

**Region-Wise Analysis**:
The average wastewater treatment percentages were computed for each region and cluster.
Visualizations were created to illustrate regional trends and the distribution of countries in each cluster.
High Treatment Percentage Analysis:

A new variable, high_treatment, was created to identify countries treating more than 50% of their wastewater.
A bar plot was generated to showcase the count of countries in each region with high wastewater treatment percentages.

**Next Steps**:

Further analysis could explore correlations with other environmental performance indicators.
Temporal trends and changes over the years could be investigated for a comprehensive understanding.
Stakeholders may leverage these insights to inform policy decisions and environmental initiatives.
Note: This summary provides an overview of the initial analysis. For more detailed insights, refer to the specific sections of the R code and visualizations generated during the analysis process.
