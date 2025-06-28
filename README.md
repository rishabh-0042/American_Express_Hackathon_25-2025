# American_Express_Hackathon_25-2025

**Data Analysis Key Findings**-**f315 to f319**
The id2 column is confirmed to be present in both the training and test datasets, which is essential for the user-specific median imputation step.
Overall column medians for **f315 to f319** were calculated from the training data to serve as the final fallback imputation values.
In the training data, after the user-specific median and row-wise median imputation steps, 3905 missing values remained in columns f315 to f319. These were fully imputed using the overall column medians.
In the test data, the initial missing value count in f315 to f319 was 6726. User-specific median imputation reduced this to 109. Row-wise median imputation did not further reduce the missing values, similar to the training data. The remaining 109 missing values were successfully imputed using the overall column medians.
After applying the three-step imputation process, there are no missing values in columns f315 to f319 in both the processed training and test datasets.
