# surfs_up

Use Python with SQLAlchemy, Flask libraries to analyze a sqlite dataset.

## Overview
- Examine the differences in weather between the months of June and December for the provided dataset of Oahu.
- Determine if the weather conditions will impede on the surf and ice cream shop business. Analysis done assumes warmer temperatures are more beneficial for this type of venture, and colder climates can negatively impact surf and ice cream sales.

## Results

1. Seasonal variation in Temperature does not seem to pose a risk to the Surf and Ice Cream business.
2. June and December temperatures appear to be similar stat wise for the data sample.
3. Factors to consider for further research which may impact the Surf business include:
    - Vicinity to nearby surfing locations
    - Wind, wave height and tidal conditions
    - Local regulations
    - Wildlife
4. Factors which may directly affect the ice cream sales:
    - Population density
    - Flavor & Taste preferences
    - Quality control
5. Other factors impacting the surf and ice cream business model:
    - Price
    - Product differentiation
    - Local competition
    - Logistical constraints

## Summary


### June Temperature Statistics
- June had an average temperature of 75 degrees F, median of 75 degrees F and a standard deviation of 3.26 degrees.
- Outlier min and max temperatures range from 64 to 85 degrees respectively.
![June Stats](https://github.com/srfassihi/surfs_up/blob/bb04e60f48ab857a5c471e0c253ad609b0a4746b/Resources/June%20Statistics.png)
- The dataset resembles a normal distribution tightly concentrated around the middle using 10 evenly spaced bins:
- ![June Histogram](https://github.com/srfassihi/surfs_up/blob/bb04e60f48ab857a5c471e0c253ad609b0a4746b/Resources/June%20Temp%20Histogram.png)

### December Temperature Statistics
- December had an average temperature of 71 degrees F, median of 71 degrees F with a standard deviation of 3.75 degrees.
- Outlier min and max temperatures range from 56 to 83 degrees respectively. 
![December Stats](https://github.com/srfassihi/surfs_up/blob/bb04e60f48ab857a5c471e0c253ad609b0a4746b/Resources/Dec%20Statistics.png)
- The dataset resembles a normal distribution tightly concentrated around the middle using 10 evenly spaced bins:
- ![December Histogram](https://github.com/srfassihi/surfs_up/blob/bb04e60f48ab857a5c471e0c253ad609b0a4746b/Resources/Dec%20Temp%20Histogram.png)
