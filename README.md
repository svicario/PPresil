# PPresil
Estimates Mean, Coefficient of Variation, Day of the Year of maximum, and standard Deviation of yearly anomalies for a time series of Vegetation index. 
The original data are filtered using Harmonic model fitting. The model has 3 harmonic ( annual, semestral and quadrimestral) plus a yearly intercept.  
As input it accept a multilayer georeferenced image ( at the moment in envi format). Within each layer the date information should be expressed as last token of the layer name, with token identified by  an underscore spacer.  
The output is produced as an image of same extent with a layer for each statistics estimates.  
The program is developed within the Ecopotential and ERAplanet/GeoEssential projects
