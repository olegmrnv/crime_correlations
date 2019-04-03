# Effects of Natural Disasters on Communities
by A.M.O.K.
#
Crime data analysis (final_Oleg folder):

final for grading is here:
https://github.com/olegmrnv/crime_correlations/tree/project_final
 
notebooks
 - data_cleanup_TX.ipynb
 - data_cleanup_VA.ipynb
 
 data_cleanup scripts reads raw data, pulls API info and creates csv files with usable data only. One script per state. 
 
 - data_analysis_TX.ipynb 
 - data_analysis_VA.ipynb
 - API key from https://crime-data-explorer.fr.cloud.gov/api

data_analysis reads filtered data and creates graphs and plots for visual data evaluation. 
 
data
 - CSV files located in “data” folder 
##
Agencies (Final_Amy folder):
 
notebooks
 - tx_map_part_agencies.ipynb
 - va_map_part_agencies.ipynb

Notebooks create a heatmap showing agencies available to pull API in Texas and Virginia. (Final_Amy/data/cleandata/)

Will need to use GMAPS API key from https://cloud.google.com/maps-platform/ to run notebooks:

data/clean_data
 - tx2008cde_agencies.csv
 - va2011cde_agencies.csv

reports
 - All NIBRS Participating Texas Agencies 2008.png
 - All NIBRS Participating Virginia Agencies 2011.png
##
Population (Final_Kundyz folder):

notebooks
 - Work for Population 2004-2015 Galveston City/Louisa County is in Final_Kundyz/notebooks folder.

reports
 - Graphs for Population 2004-2015 Galveston City/Louisa County are in Final_Kundyz/reports folder.

##
Median Household Income (Final Mariam folder):
 
notebooks

MHI 2004 - 2015 Galveston County.ipynp
MHI 2004 - 2015 Louisa County.ipynp

Must use API key for US Census

data

Data was pulled using API and then manually copied / pasted into Excel and saved as .csv 
Then, and bar charts were created and saved as .xlsx
mhi_galv_county.xlsx
mhi_louisa_county.xlsx
