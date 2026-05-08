# Case_Study_Project5_Data_Analysis_With_Python
## Does Annual Household Income Play a Role In Minority's Political Party Identification In UK?
### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendation)

### Project Overview

This question contributes to the broader debate in political science about the determinants of voting behavior. While traditional models emphasize economic factors such as income and social class, this study explores whether cultural and ethnic identity may play a more significant role among minority populations in the UK.

### Data Sources

Primary dataset used for this analysis which are provided in the files attached to this project are:
- Data file: BSE_2010.dta 
- Format: Stata (.dta) 
- Source: British Election Study - Ethnic Minority Survey 201016

### Tools
 
- Python: Data Analysis

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Reading the .dta file,
2. Column renaming,
3. Value label mapping,
4. Filtering invalid values

### Exploratory Data Analysis (EDA)

EDA involves exploring the data to answer key questions, such as:

- Does ethnicity drive people closer to party?
- Does income drive people closer to party?
- Does income influence party identification among the minorities?

### Data Analysis

Include some interesting code/ features worked with

```python
Table1 = pd.crosstab (df_labeled[‘Five Ethnicities Label’], df_labeled[‘Closer to Party Label’])
Print(table1)
```

### Result/Findings

The analysis results are summarized as follows:
1. Ethnicity does drive people closer to party.
2. Income does not drive people closer to party.
3. Income does not influence party identification among the minorities.
	
### Recommendations

Based on the analysis, we recommend the following actions:
- Political parties seeking to attract ethnic minority voters should focus on culturally relevant messaging tailored to each ethnic group rather than strategies based on economic segmentation.
- Although income does not drive party identification among the minority group. Government still need to work on achieving equal income distribution among the citizens.
- Having understood the relationship between income and political preferences among minorities. Stakeholders should shape more inclusive and representative policy agendas.

### Limitations

- This study only provides us with analysis of The British Election Study Ethnic Minority Survey 2010 collected data from 2,787 respondents across five ethnic groups: Indian, Pakistani, Bangladeshi, Black Caribbean, and Black African in the UK.
While a data of just a single year of election may not be enough to give a reliable data to make inferences from. Analysis of a consecutive 3 to 4 different years of election could have given a more reliable data to make inferences from during analysis.

### References
	
- [stack Overflow](https://stack.com)
- Statistics for Data Analysis by Using Python:	Dr. Sandeep Kumar (Quality Guru Inc.) - UDEMY
- Complete SQL Bootcamp - Go from Zero to Hero:     Dr. Jose Portilla (Pierian Training) - UDEMY
- Complete Microsoft Power BI:  By Nikolai Schuler, (Ligency, SuperDataScience Team) - UDEMY
- Microsoft Excel – Excel from Beginner to Advanced:	By Kyle Pew - UDEMY
- Tableau A-Z - Hands-on Tableau:	By Kirill Eremenko, (SuperData ScienceTeam, Ligency)
- Python for Time Series Data Analysis:		By Dr. Jose Portilla (Pierian Training) - UDEMY
- Complete KoboToolbox (ODK), google form Training:	By Alexander Mtembenuzeni - UDEMY
- Map Academy: Get mapping quickly, with QGIS:	By Professor Alasdair Rae - UDEMY
- Map Academy: Taking QGIS to the next level: 		By Professor Alasdair Rae - UDEMY
- The Supervised Machine Learning Bootcamp:		By 365 Careers - UDEMY
