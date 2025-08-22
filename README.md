# Google Drive Link: https://drive.google.com/drive/folders/1mu-WfIV6xb8wmY4Jw6lfiCJGgr1TAI7v?usp=share_link
Inspection: 
    1. Checked for missing values/ outliers/ duplicates of rows and routes
    2. Used Jupyter on Anaconda and performed procedures in celled programs
    3. Used boxplot and histogram for each column's variable (check skewers/outliers)
    
Clean:
    1. Inspection from the previous step shows very high quality, without a single null/negative/duplicates. 
    2. Possible ways to clean include deleting the Freights and Mails and sort data by origin in different sheets. However, they            won't affect calculation, and it's safer to have a full dataset in case they are needed to give recommendation in the end.

Understand and Intepret:
    1. Identified the most and least trafficked routes by organizing the top 10 and bottom 10 of the routes by traffic volume.
    2. Analyzed data for year trends and passenger volume by location and routes. 
    3. Generated line graph/histogram/horizontal bar chart to support reasoning for part 2.

Build Models:
    1. Picked Sydney --> Auckland (the key factors = 6-12 months future forecast)
    2. Decided which models to use (with strong seasonality): Holt-Winters (triple exponential smoothing), Seasonal Naive and SARIMA 
    3. Set the last year (1988.7-1989.7) as a validation period and generate validation forecast, calculate MAPE and RSME
    4. Generated foreccast of the next 6-12 months with all models and piced seasonal naive model as the most accurate because it           has the smallest MAPE (Mean Absolute Percentage Error) 
    
Preparation:
    1. Wrote response and organized visualizations, including evauation and recommendations
