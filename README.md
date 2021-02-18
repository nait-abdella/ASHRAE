#### Team : 
- YECHCHI Sif-Eddine 
- NAIT ABDELLA
- EL ADAMI Hichem 

Pour nous contacter, rendez-vous sur [Discord](https://discord.gg/Tz7u4JWW) !


## Subject: ASHRAE Energy Prediction

#### Données:

The data contains 3 files: 

* train : de taille (20216100, 4)
* building_meta : de taille (1449, 6)
* weather_train : de taille (139773, 9) 


First, we have merged the files to have a single file that we called train.
The size of the train file is: (20216100, 16).

Then, we have reduced the memory of the data:

* Memory usage of dataframe was: 2622.02 MB
* Memory usage after optimization: 790.84 MB

=> Decreased by 69.8%

Missing values: 
![heatmap of missing values](Images/na_values.png)

There are the percentages of missing values for each variable: 

floor_count	:82.65 %

year_built : 59.99 %

cloud_coverage	:	43.65 %

precip_depth_1_hr	:	18.54 %

wind_direction	:	7.16 %

sea_level_pressure	:	6.09 %

wind_speed	: 0.71 %

dew_temperature	:	0.49 %

Other variables .. : 0%


 

