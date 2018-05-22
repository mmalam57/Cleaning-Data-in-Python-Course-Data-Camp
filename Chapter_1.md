# Cleaning-Data-in-Python-Course-Data-Camp
#Excellent! Notice that the columns 'Initial Cost' 
#and 'Total Est. Fee' are of type object. T
#he currency sign in the beginning of each value in these columns needs to be removed, 
#and the columns need to be converted to numeric. In the full DataFrame, note that there are a lot of missing values. 
#You saw in the previous exercise that there are also a lot of 0 values. Given the amount of data that is 
#missing in the full dataset, it's highly likely that these 0 values represent missing data.

# Import pandas
import pandas as pd

# Read the file into a DataFrame: df
df = pd.read_csv('dob_job_application_filings_subset.csv')

# Print the head of df
print(df.head())

# Print the tail of df
print(df.tail())

# Print the shape of df
print(df.shape)

# Print the columns of df
print(df.columns)

# Print the head and tail of df_subset
print(df_subset.head())
print(df_subset.tail())

