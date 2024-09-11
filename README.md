# Machine Learning-based Forecasting for Building Energy Consumption

## About me
I am a graduate in energy engineering at the University of Hong Kong, my master's degree research delved into investigating the factors influencing building energy consumption within the framework of a practical data science and analytic study.

## Problem Definition
The Internet of Things (IoT) is a rapidly growing trend that allows for the collection of vast amounts of data, including electricity and gas bills, as well as real-time weather information. This interconnected network of physical devices, equipped with sensors, software, and internet connectivity, facilitates seamless data exchange.

Through the utilization of IoT technologies, a substantial amount of data can be amassed, providing a solid foundation for this research. By leveraging valuable data obtained from sensors and public sources, informed decisions can be made to optimize energy consumption and enhance building performance. However, simply collecting data is not sufficient.

To accurately predict energy usage, refine energy management strategies, and extract meaningful insights from the data, advanced data science techniques are indispensable. Therefore, the problem statement of this research focuses on the application of data science and machine learning techniques to overcome these barriers and harness the power of data-driven energy management and prediction in smart buildings.

## Dataset
The dataset used in this research comes from ASHRAE-Great Energy Predictor III which is a Kaggle competition by the American Society of Heating and Air-Conditioning Engineers (ASHRAE). ASHRAE is a professional engineering organization of heating, ventilation, air conditioning, and refrigeration in the United States that was founded in 1894.

The dataset contains an extensive amount of training data, comprising over 20 million data points. These data points were collected from over 2,000 energy meters installed in about 1,500 buildings. The data was sourced from 16 different locations within the United States. The collection period spans one year, specifically in 2016. The dataset offers a comprehensive range of information, including historical weather data and energy usage.
This wealth of information enables detailed analysis and exploration of the relationship between weather conditions, building information, and energy usage patterns. The dataset's detailed information is provided below.

| Dataset             | Name              | Description                                                                                                       | Unit |
|---------------------|-------------------|------------------------------------------------------------------------------------------------------------------|------|
| train.csv           | building_id       | ID of the building                                                                                               |      |
|                     | meter             | ID of the meter type where 0 represents electricity, 1 represents chilled water, 2 represents steam, and 4 represents hot water |      |
|                     | timestamp         | Current time of measurement capture in 1 hour interval                                                           |      |
|                     | meter_reading     | Energy consumption                                                                                               | kWh  |
|                     | site_id           | ID of the location of building                                                                                   |      |
| weather_train.csv   | air_temperature   | The temperature of the air                                                                                       | °C   |
|                     | cloud_coverage    | Sky covered in clouds with the range of 0 to 9                                                                   | oktas|
|                     | dew_temperature   | The temperature of air which it must be cooled to become saturated with water vapor                             | °C   |
|                     | precip_depth_1_hr | The quantity of rainfall in 1 hour                                                                               | mm   |
|                     | sea_level_pressure| The atmospheric pressure at sea level                                                                            | hPa  |
|                     | wind_direction    | Direction of wind ranging from 0 to 360                                                                          |      |
|                     | wind_speed        | Speed of wind                                                                                                    | m/s  |
| building_metadata.csv   | site_id   | ID of the location of building                                                                                       |      |
|                     | building_id    | ID of the building                                                                   |   |
|                     | primary_use   | Predominant usage classification for building                             |    |
|                     | square_feet | Total area of the building                                                                               | m2   |
|                     | year_built | Year of building construction                                                                            |   |
|                     | floor_count    | Amount of building floors                                                                          |     |

The target variable for this building energy consumption forecasting is meter_reading, representing energy consumption measured in kWh. It focuses on four types of meters which are electricity, chilled water, steam, and hot water. These meters cover the main energy sources used in modern buildings.

## Result
To Be Continued
