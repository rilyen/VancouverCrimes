# Vancouver Crime Rates

This project explores the effect of socioeconomic factors on the number of crimes in Vancouver as well as investigating the possibility of modelling other urban cities using Vancouver’s population demographics.

## Requirements
To run this project from start to finish, you will need:
- [Python 3.10](https://www.python.org/downloads/)

### 2. Processing Data in Python
After obtaining the data from R, we can then move to Python for data cleaning and analysis.

The following libraries are needed:
- pandas
- numpy
- geopandas
- matplotlib
- folium
- seaborn

Which can be done through the terminal:
```
pip install --user pandas numpy geopandas matplotlib folium seaborn
```
Run the files to create the visualizations:
```
python3 initial_plots.py
python3 vancouver_crime_map.py
```
#### Expected Outputs
- ##### `initial_plots.py`
    - In `initial_plot/van` folder:
        - histogram of vancouver log(crime_rate)
        - boxplot of vancouver log(crime rate)
        - scatter plots of crime_rate vs all other features with linear regression
        - scatter plots of log(crime_rate) vs all other features with linear regression
        - histogram of residuals of log(crime_rate) vs all other features
        - txt file with information from the linear regression

- ##### `vancouver_crime_map.py`
    - A choropleth map of crime count in Vancouver `vancouver_crime_map.html`
    - Can be opened in the browser for an interactive visualization

