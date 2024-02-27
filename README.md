# Explore rainfall patterns in Southern Israel.

## Overview

Twenty-five meteorological stations in Southern Israel were assessed based on data from the [Israel Meteorological Service (IMS)](https://ims.gov.il/he/data_gov).
Analyzed with Python.

## discussion

For the analysis of rainfall data, relying on a single trend line proves challenging due 
to the substantial correlation in the dataset.
The data doesn't conform neatly to a linear trend, as illustrated in the provided 
[Tableau viz](https://public.tableau.com/shared/3Z56PMGPD?:display_count=n&:origin=viz_share_link)
. 
It becomes evident that selecting different subsets of years for measurements can result 
in trend lines with varying slopes, 
either positive or negative.

It is implausible that the natural patterns of rainfall are influenced by the timing of our measurements. 
In this study, we opted to consider all possible trend lines, capturing their respective slopes in matrices.
This comprehensive approach unveils a discernible decrease in rainfall amounts over time in the 
southern region of the State of Israel.

The matrices, graphically presented as heat maps in the project, underscore the fluctuating slopes of the trend lines. 
Notably, when considering a span of 100 years, the slope of the curve line is not consistently constant. 
However, with a more focused timeframe, such as a minimum of 10 years, a predominant red hue emerges, 
especially in the upper corner. This pattern suggests a discernible decline in rainfall amounts over time.

## Libraries

1. NumPy
2. Matplotlib
3. Seaborn





## IMG of the Tableau (power  BI abandoned due to permission issues):
<img src="power BI 1.png" alt="Alt Text" width="300">
<img src="power BI 2.png" alt="Alt Text" width="300">
<br>
<img src="map and toltip.png" alt="Alt Text" width="200">

