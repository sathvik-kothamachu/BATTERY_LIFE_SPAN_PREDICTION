# BATTERY_LIFE_SPAN_PREDICTION
The growing demand for reliable energy storage
has led to major progress in using machine learning (ML) to
predict battery wear and enhance the performance of lithium
ion (Li-ion) batteries. This study introduces a data-driven
multiclass classification framework designed to predict battery
health states and estimate their remaining useful life (RUL). The
dataset includes important electrochemical parameters such as
charge and discharge current, voltage, temperature, cycle count,
and state of health (SOH). To make the data easier to interpret
and more suitable for classification, the continuous RUL values
are grouped into three clear categories: low, medium, and high
degradation. Several ML algorithms, including Random Forest,
XGBoost, and LightGBM, are trained and fine-tuned using grid
search cross-validation to measure predictive performance. An
extensive Exploratory Data Analysis (EDA) is carried out to
understand how different features relate to each other and how
they influence battery degradation. Out of all the models we
tried, LightGBM stood out. It nailed both accuracy and speed.
XGBoost was solid too—it kept performing well no matter
how much the battery had degraded. So, with this framework,
you get accurate battery health checks and a real shot at
staying ahead with smarter, data-driven maintenance for electric
vehicles and renewable energy setups.
