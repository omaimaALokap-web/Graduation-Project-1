# Graduation-Project-1
## Project Overview
This project aims to predict whether a Near-Earth Object (NEO) is hazardous based on various astronomical features. Accurate prediction of hazardous NEOs is crucial for planetary defense and mitigating potential impacts on Earth.

#### Dataset Description
The dataset comprises information on NEOs, including:

#### Features:
* neo_id: Unique identifier for each NEO.
* name: Name of the NEO.
* absolute_magnitude: Intrinsic brightness of the NEO.
* estimated_diameter_min and estimated_diameter_max: Estimated size range of the NEO.
* orbiting_body: Celestial body around which the NEO orbits.
* relative_velocity: Speed of the NEO relative to Earth.
* miss_distance: Closest distance between the NEO and Earth.

* Target Variable:
is_hazardous: Boolean indicating if the NEO is potentially hazardous.


## Key Steps and Methodologies
###  1. Data Preprocessing
* Handling Missing Values: Missing values in absolute_magnitude, estimated_diameter_min, and estimated_diameter_max were imputed using the median of the respective columns.


* Scaling Numerical Features: Numerical features were scaled using StandardScaler to ensure all features are on the same scale.

* Handling Imbalanced Classes: The target variable is_hazardous was imbalanced. Techniques such as Random Oversampling and SMOTE were applied to balance the dataset.

