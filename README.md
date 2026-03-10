# covid-dash
[Hosted here](https://songgo1.github.io/covid-dash/)

In response to the COVID-19 pandemic, local and federal agencies around the world began tracking cases to mediate spread. This data was aggregated by Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) and was published on an online dashboard that allowed real time tracking of the COVID-19 pandemic globally. In total, JHU CSSE collected data from 199 countries from 1/22/20 to 3/9/23. The dataset also contains case counts for the Summer 2020 and Winter 2022 Olympics. 

This applet allows users to inspect the daily or cumulative case counts for countries of interest based off the data provided in the COVID-19 confirmed global time series dataset. Data is displayed as a bar chart for each country/region. The bar chart is colored by state, province, or dependency data if information was available. Users can also inspect how counts for chosen dates compare to the entire time series in the line chart for countries of interest. Lastly, users can inspect the map to see count data geographically.

Interactive graphics were generated using plotly graphic library. Applet was built using Streamlit and html was generated using StliteSharing. 

Limitations
Some daily counts may appear negative due to retroactive corrections in cumulative reporting from source data.
