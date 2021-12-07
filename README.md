# Time-Series-Data-Handling-in-Python

## Pre-processing Timeseries Data
Pandas contains extensive capabilities and features for working with time series data for all domains. Using the NumPy datetime64 and timedelta64 dtypes, pandas has consolidated a large number of features from other Python libraries like scikits.timeseries as well as created a tremendous amount of new functionality for manipulating time series data.

You can read more about the other directives and datetime library here: https://docs.python.org/3/library/datetime.html

## CHALLENGES WITH TIME DATA
### DEALING WITH TIME ZONES
•	If you have the dataset of a specific time zone. You can tell pandas about the local time zone and later you can convert it into different time zones.

•	Use function dt.tz_localize to set the local time zone.

•	Use the function tz_convert to convert the timezone.
