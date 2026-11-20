**Puerto Rico Energy Disasters and Push For Renewable Energy**
Puerto Rico's energy infrastructure has a volatile history of failure, both from weak infrastructure and natural disasters that destroy its infrastructure.  This project explores the relationship between if energy failure, increases people's dependency on renewable energy. 

**Does energy failure lead to an uptick in renewable energy dependence in Puerto Rico?**

**Data:**
Outage data is collected from 2020-2025 and show time, county, state of the outage. https://figshare.com/articles/dataset/The_Environment_for_Analysis_of_Geo-Located_Energy_Information_s_Recorded_Electricity_Outages_2014-2022/24237376?file=53581661

Percent renewable data from 1990-2022 shows percent renewable consumption over time. 
https://www.worldviewdata.com/countries/puerto-rico/renewable-energy-consumption

**Structure:**
  ``` pr_energy 
    clean_data 
    figures 
    raw_data  
      renewable_energy_pct.csv
      eaglei_outages_2020
      eaglei_outages_2021
      eaglei_outages_2022
      eaglei_outages_2023
      eaglei_outages_2024
      eaglei_outages_2025
    scripts
      0_project_setup
      1_data_clean 
```

 **How to Run:**
    Mount to google drive in R, then switch to Python 
    Run Project Set up, then data clean 

**Cleaning**
  The cleaned data came from larger data bases, and Puerto Rico only data was extrapolated. That data was then joined by year.

**Status**
  Next Steps Include: 
    -analyzing data to see if there are trends, includes calculating the difference in percent change 
    -make graphs of difference to demonstrate that relationship, if any 
  
