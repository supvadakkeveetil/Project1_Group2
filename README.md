# Project1_Group2
## Exploratory Data Analysis Report 
Detailed report for analysis can be found under the link 
(https://github.com/supvadakkeveetil/Project1_Group2/blob/main/EDA_Carbon_Emissions_Report.docx)

### Project Title: Carbon Emissions across America: Unveiling Regional Disparities, Key Contributors
#### Introduction
This report presents a Comprehensive Analysis of CO2 Emissions in the United States, focusing on trends across various sectors and individual states. The objective is to understand the patterns, variations, and potential impacts of CO2 emissions
The motivation for the project comes from the need to tackle the Environmental challenges and the leading causes for these issues. 
#### Data Description - The datasets are in the folder data (https://github.com/supvadakkeveetil/Project1_Group2/tree/main/data)
The Dataset comprises of detailed Co2 emissions across different sectors including Transportation, Electric Power, Industrial Sectors, and others. The data spans a timeline from 2010 to 2021 covering both national and state-level analysis.
1.	US EPA (Environmental Protection Agency – Data (Historical) on the Greenhouse gas emissions in the United States.
2.	US EIA (Energy Information Administration) – Data on State level emissions, Energy production and Electricity Generation Source.
#### Data Cleaning and Preparation- The steps involved - Jupyter notebook ( DataExp_Cleaning_P1G2.ipynb) https://github.com/supvadakkeveetil/Project1_Group2/blob/main/DataExp_Cleaning_P1G2.ipynb
1.	Import Libraries – Import the necessary libraries, like Pandas, Matplotlib. 
2.	Load Data into the Data Frame – loading the US and Statewise datasets
Converted our data from Excel and CSV files into Pandas Data Frames using the pandas .read_excel() and .read_csv()
3.	Preliminary Data Examination –Used various Pandas function to get an overview of the data.  Looked at the structure of the data frame using .head(), the .info() to check the datatypes and values, and the .describe() for Summary Statistics 
4.	Data Cleaning
•	Handling missing values – Checked for missing values in the data frame using the   df.is.null().sum()
•	Checking for duplicates – using the df.duplicates()
•	Removal on unnecessary Data –drop() function
•	Quality checks on the data – looked to see the final structure of the cleaned-up data frame and made sure that the information and format is consistent across the Data Frames used for our analysis
5.	Data Visualizations – Bar charts and Plots for showing the Trends across the years for different states, sectors.
#### Data Analysis – Visualizing datasets, plotting, and finding answers to the research questions (Jupyter Notebook - Visualization_P1G2.ipynb) https://github.com/supvadakkeveetil/Project1_Group2/blob/main/Visualization_P1G2.ipynb
#### Analysis Report - (https://github.com/supvadakkeveetil/Project1_Group2/blob/main/EDA_Carbon_Emissions_Report.docx)

### Links and information to the files
1. Data sets Folder - [
(https://github.com/supvadakkeveetil/Project1_Group2/tree/main/data)](https://github.com/supvadakkeveetil/Project1_Group2/tree/main/data)
2. Data Cleaning Jupyter Notebook - [
(https://github.com/supvadakkeveetil/Project1_Group2/blob/main/DataExp_Cleaning_P1G2.ipynb)](https://github.com/supvadakkeveetil/Project1_Group2/blob/main/DataExp_Cleaning_P1G2.ipynb)
3. Data Visualization Jupyter Notebook - 
[(https://github.com/supvadakkeveetil/Project1_Group2/blob/main/Visualization_P1G2.ipynb)](https://github.com/supvadakkeveetil/Project1_Group2/blob/main/Visualization_P1G2.ipynb)
4. Output Visualizations Folder-  [https://github.com/supvadakkeveetil/Project1_Group2/tree/main/output_data](https://github.com/supvadakkeveetil/Project1_Group2/tree/main/output_data)
5. Presentation - [
(https://github.com/supvadakkeveetil/Project1_Group2/blob/main/Project1Group2_Presentation.pptx)](https://github.com/supvadakkeveetil/Project1_Group2/blob/main/Project1Group2_Presentation.pptx)
6. Exploratory Data Analysis Report - [
(https://github.com/supvadakkeveetil/Project1_Group2/blob/main/EDA_Carbon_Emissions_Report.docx)](https://github.com/supvadakkeveetil/Project1_Group2/blob/main/EDA_Carbon_Emissions_Report.docx)
### References
1.	https://www.eia.gov/environment/emissions/state/
2.	https://cfpub.epa.gov/ghgdata/inventoryexplorer/#allsectors/allsectors/allgas/gas/all
3.	https://www.statista.com/statistics/220174/total-us-electricity-net-generation-by-fuel/
4.	https://www.epa.gov/ghgemissions/sources-greenhouse-gas-emissions

