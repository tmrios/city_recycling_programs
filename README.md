# README
To normalize the data, rows and columns were formatted and values were edited to be consistent with one another. For example, the original Providence dataset chose the following format for the “fiscal_year” attribute: “6/30/2019 0:00.” I edited this value to “2019” to match the fiscal year values for New York City and Franklin. 

Moreover, data was enriched by adding city population data pulled from the U.S. Census Bureau to contextualize and improve the reuse potential of the dataset as a whole. 

Note that this dataset reflects New York City measurements of recycling and refuse tonnage per day. While New York City measures daily counts of recycling and refuse tonnage, Providence and Franklin measure recycling and refuse tonnage annually. This is an important distinction in this dataset. 

The total recycling value was manually calculated by adding metal, glass, and plastic (MPG) tonnage to paper tonnage. Organics were not included in the calculation. It is unclear what materials are included in total recycling values as reported by Providence and Franklin. This necessitates further research. 
The format used to name files is: projectName_dataType_version. There are two data files in this repository: RecyclingPrograms_Raw_VS1.csv and RecyclingPrograms_Normal_VS1.csv.

