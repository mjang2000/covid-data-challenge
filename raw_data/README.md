# mobility-covid19
## `apple_data` (Last Updated 4/18)

`/apple_mobility_trends.csv`: Sorted by country and major cities. 

Source: https://www.apple.com/covid19/mobility

tldr: Uses routing requests to describe countries and major cities and their mobility trends through driving, walking, and transit. 

Day defined as midnight-to-midnight, Pacific time. Cities represent usage in greater metropolitan areas and are stably defined during this period. In many countries/regions and cities, relative volume has increased since January 13th, consistent with normal, seasonal usage of Apple Maps. Day of week effects are important to normalize as you use this data.

Data that is sent from users’ devices to the Maps service is associated with random, rotating identifiers so Apple doesn’t have a profile of your movements and searches. Apple Maps has no demographic information about Apple users, so it's impossible to make any statements about the representativeness of usage against the overall population.


## `google_data` (Last Updated 4/11)


`/mobility_report_US.csv`: Sorted by county.

`/mobility_report_countries.csv`: Sorted by country and states.

`/mobility_report_global.csv`: All data.

Source: https://www.google.com/covid19/mobility and https://github.com/ActiveConclusion/COVID19_mobility

tldr: Describes the mobility of *retail, grocery and pharmacy, parks, transit stations, workplaces, and residential*.
The CSV file shows a relative volume of directions requests per country/region or city compared to a baseline volume on January 13th, 2020.

In early April 2020, Google started publishing an early release of COVID-19 Community Mobility Reports to provide insights into what has changed in response to work from home, shelter in place, and other policies aimed at flattening the curve of this pandemic. These reports have been developed to be helpful while adhering to our stringent privacy protocols and policies. 

These Community Mobility Reports aim to provide insights into what has changed in response to policies aimed at combating COVID-19. The reports chart movement trends over time by geography, across different categories of places such as retail and recreation, groceries and pharmacies, parks, transit stations, workplaces, and residential.


## `csse_data` (Last Updated 4/18)


`/archived_data/`: Probably won't need.

`/csee_covid_19_data/`: Sorted by country, states, and cities.

`/who_covid_19_situation_reports/`: Self explanatory, has time series data. (Updated 4/3)


Source: https://github.com/CSSEGISandData/COVID-19

This is the data repository for the 2019 Novel Coronavirus Visual Dashboard operated by the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE). Also, Supported by ESRI Living Atlas Team and the Johns Hopkins University Applied Physics Lab (JHU APL).

## `nytimes_data` (Last Updated 4/19)

`/us-counties.csv`: Daily number of cases and deaths by county (includes FIPS code)

`/us-states.csv`: Daily number of cases and deaths by state (includes DC and territories)

`/us.csv`: Daily number of cases and deaths nationwide


Souce: https://github.com/nytimes/covid-19-data.git

If you use this data, you must attribute it to “The New York Times” in any publication. If you would like a more expanded description of the data, you could say “Data from The New York Times, based on reports from state and local health agencies.”

## `population_data` (Last Updated 4/19)

`/co-est2019-annres.xlsx`: Population Data from 2010 to 2019 sorted by county.
'PEP_2018_PEPANNRES_with_ann.csv': Population Data from 2010 to 2018 sorted by city.
Souce: https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-total.html
https://www.census.gov/data/datasets/time-series/demo/popest/2010s-total-cities-and-towns.html

Population Data from 2010 to 2019 sorted by county, as of July 1 for each year based on the 2010 census.

To Be documented: 
- 
## `kff_data` (Last Updated 4/23)

## `turnstile_data` (Last Updated 4/19)

## `zipcode_data` (Last Updated 4/23)

## `USDA_data` (Last Updated 4/23)






