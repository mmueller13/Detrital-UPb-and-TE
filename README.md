# Detrital-PbCorrections-and-TREEs
Jupyter notebooks for U-Pb timeseries, detrital common Pb corrections, U-Pb plotter, rutile trace element visualization, trace element PCA

### <br> 1. UPb-Timeseries
Python code for displaying U-Pb timeseries data from Element2 txt files. 

Example data given in zip folder: ExampleDataset-UPbTimeseries-Muelleretal-21RtF.zip <br> 


### <br> 2. Detrital-Common-Pb-Corrections
Python code for common Pb corrections of detrital U-Pb data. 

Example data given in: ExampleDataset-DetritalCommonPbCorrections-Muelleretal_Unknowns.xlsx


### <br> 3. UPb-Plotter
Python code for plotting U-Pb data in Tera-Wasserburg space and exploring discordance metrics and U-Pb uncertainty filtering. Uses the data output from Detrital-Common-Pb-Corrections.

Example data given in: ExampleData-UPbPlotter-Muelleretal.xlsx


### <br> 4. Rutile-Trace-Elements
Python code for visualizing detrital rutile trace element geochemistry data, including TiO2 polymorphs, mafic and pelitic protoliths, Zr-in-rutile temperature, and exploration of low U contents and concordance. Uses data output from UPb-Plotter (which itself uses data output from Detrital-Common-Pb-Corrections).

Example data given in: ExampleData-RutileTraceElements-Muelleretal.xlsx. 
<br> Example data can be displayed with the Triebold et al., (2011, Contrib Mineral Petrol) TiO2 polymorphs dataset: Triebold_etal_2011_Data.xlsx


### <br> 5. Detrital-PCA-R
R code for performing principal component analysis on trace element geochemistry data. To run the R code in a jupyter notebook, R must be installed on the local computer.

Example data given in: ExampleData-RutileTraceElements-Muelleretal.xlsx
