# code to produce the figures included in the BAMS "State of the Climate" report section on Pacific Convergence Zones 

1) download the updated monthly CMORPH dataset from the KNMI Climate Explorer at: [https://climexp.knmi.nl/](https://climexp.knmi.nl/) 

2) in `notebooks`: 

+ [plot_monthly_maps.ipynb](https://github.com/nicolasfauchereau/BAMS_SOTC_2019/blob/master/notebooks/plot_monthly_maps.ipynb) calculates the anomalies (WRT to 1998 - 2018 climatology) in mm and percentage of normal then plots (maps) the average rainfall and anomalies for a chosen date (year-month) 
+ [plot_sectors.ipynb](https://github.com/nicolasfauchereau/BAMS_SOTC_2019/blob/master/notebooks/plot_sectors.ipynb) calculates the longitudinal sectors averages and plots (x-axis = Rainfall in mm, y-axis = latitude)
+ [plot_ENSOs_vs_current_year.ipynb](https://github.com/nicolasfauchereau/BAMS_SOTC_2019/blob/master/notebooks/plot_ENSOs_vs_current_year.ipynb) calculates longitudinal sector averages as above and compares a chosen 3 months season to recent ENSO years composites (La Nina, El Nino and Neutral) based on the 3 months values of the Oceanic Nino Index (ONI) downloaded from NOAA at [https://www.cpc.ncep.noaa.gov/data/indices/oni.ascii.txt](https://www.cpc.ncep.noaa.gov/data/indices/oni.ascii.txt). 

