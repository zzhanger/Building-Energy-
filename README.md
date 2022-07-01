Energy use in buildings
Estimating building energy consumption is critical for sustainable urban planning. The first step to estimate building energy consumption is to determine the Gross Floor Area (GFA). In this project, the following processes were conducted to get GFA of the desired city:
* Obtain the building footprint data from OpenStreetMap
* Obtain the Digital Surface Model (DSM) from OpenTopography (including buildings and infrastructures)
* Using ArcMap, create random sample point in building footprint, and generate buffer for building footprint and create random sample points in buffer.
* Summary statistics of mean of samples in building footprint and minimum of samples in buffer. Building height is achieved.
* Refer to others' sensitivity analysis on floor height, and calculate building foot print area by ArcMap, and finally GFA can be calculated.
The second step is to get the building energy intensity and cooling energy intensity, which requires simulation in EnergyPlus. the detailed steps show here:
* Access standard 90.1 Prototype Building Models and specific location weather files
* Simulate the energy use of 16 commercial prototypes under specific weather conditions (Apartments are classified to domestic and others are classified to non-domestic)
* Extract desired data from simulation results, including building energy use intensity and cooling energy intensity
The aim of this study is to investigate whether the seawater cooled district cooling system has potential to save energy and GHG for cities, therefore, the alternative approach, building photovoltaic solar panels on rooftop, is compared. PVWatts Calculator is utilized.
