# Understanding-Applicant-Trends-in-Nigeria
Understanding Applicant Trends in Nigeria: A Look at Different Regions

# Nigerian CDCFIB Recruitment Analysis

## Overview

This notebook analyzes recruitment data from the CDCFIB website, focusing on the distribution of applicants across Nigerian states and geopolitical zones. It also calculates the application rate per 100,000 population for each state by merging with population data.

## Data Sources

* **Recruitment Data:** Scraped from the CDCFIB recruitment website (`https://recruitment.cdcfib.gov.ng/`) using Selenium and Pandas.
* **Population Data:** Loaded from an Excel file (`nigeria_states_population (1).xlsx`).

## Analysis Steps

1. **Data Extraction:** Scraped the recruitment table from the CDCFIB website.
2. **Data Wrangling:**
    - Reshaped the extracted table to have 'STATE' and 'APPLICANTS' columns.
    - Cleaned state names by stripping whitespace and converting to lowercase.
    - Converted 'APPLICANTS' to integer format.
3. **Geopolitical Zone Mapping:** Mapped each state to its corresponding Nigerian geopolitical zone using a predefined dictionary.
4. **Applicant Analysis by State and Zone:**
    - Calculated the total number of applicants per state and per geopolitical zone.
    - Visualized the number of applicants by state and zone using bar charts.
5. **Population Data Integration:** Merged the applicant data with population data based on state names.
6. **Application Rate Calculation:** Calculated the application rate per 100,000 population for each state.
7. **Top States by Application Rate:** Identified and visualized the top 3 states with the highest application rates per 100,000 population.

## Key Findings

* The total number of applicants and their distribution across states and geopolitical zones were determined.
* The North Central zone had the highest number of applicants, followed by the North West.
* The application rate per 100,000 population varied significantly across states.
* Kogi, Nasarawa, and Kwara states had the highest application rates per 100,000 population.

## Visualizations

The notebook includes the following visualizations:

* Bar chart showing the number of applicants by state.
* Bar chart showing the number of applicants by geopolitical zone.
* Bar chart showing the percentage of applicants by state.
* Bar chart showing the percentage of applicants by geopolitical zone.
* Bar chart showing the application rate per 100,000 population by state.
* Bar chart showing the application rate per 100,000 population for the top 3 states.

## Conclusion

This analysis provides insights into the geographical distribution of applicants for the CDCFIB recruitment and highlights states with high application intensity relative to their population. This information can be valuable for targeted outreach and resource allocation in future recruitment drives.
