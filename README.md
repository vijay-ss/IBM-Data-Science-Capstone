# Opening a New Fitness Centre in Toronto, Canada
### An IBM Data Science Capstone Project
Contains project files used for the final capstone project.

## Overview

With the popularity of fitness centres and gyms on the rise in recent years, a lucrative business opportunity exists for those seeking to open one of their own in Toronto, Canada. This research project examined the ideal location to open a fitness centre in Toronto, based on characteristics within local neighbourhoods. Neighbourhood data was extracted from Wikipedia, neighbourhood data was pulled using the Foursquare Develop API, and transformed in such a way to create 5 clusters for the k-Means Clustering machine learning algorithm. Results showed that Downtown Toronto has the most local venues for which consider when opening the business. The findings suggested that the financial district has little to no competition, which might yield the most success for the business venture.

## File versions
- Week 1-4 are preliminary data analysis files, found in the 'project_files' folder
- The final files are included in the root directory and include the final pdf article and notebook:
  - Final Code: Toronto Neighbourhood Clustering.pynb
  - Final Report: Opening a New Fitness Centre in Toronto v1.pdf

### Prerequisites
 - Python 3.7
 - JupyterLab
 - Packages: pandas, numpy, scikit-learn, matplotlib, seaborn, folium, geopy, beautifulsoup
 - Foursquare API developer account (free)
 
## Walkthrough

### Target Audience
The intended audience for this study is the aspiring or existing business owner who seeks to open a fitness centre in Toronto, Canada. Research indicates that as of 2018, the timing is optimal due to significant urban growth in the city. A report published by the city of Toronto suggests that urban plans aim to direct growth away from residential areas into avenues, centres and downtown.

### Data
The main driver behind the results produced from this study is the data. In order to solve the business problem, data will be gathered based on:

1. Toronto neighbourhood data. This defines the scope of the project which is limited to the city.
2. Latitude and longitudes pertaining to neighbourhoods within Toronto. This is also required to generate maps, and pull venue information.
3. Venue data from each individual neighbourhood. We will use the data to create clusters based on features within the neighbourhoods.
