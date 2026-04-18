#**Analysis of the Tender Process in Public Procurement**

#**Objective**
To analyze performance of the tender process, identify delays, and understand value patterns across categories, methods, and buyers.

#**Tools Used**
Google Colab (environment)
Python (Pandas, NumPy) - Data cleaning and analysis
Matplotlib, Seaborn – Data visualization
Power BI – Interactive dashboard creation

#**Data Modeling**
Cleaned dataset by handling missing values and inconsistent entries
Created new features:
tender_value_in_cr for better readability
process_duration was derived to validate date columns and identify data errors
Categorized and structured data for analysis across:
Procurement methods
Tender stages
Buyers and classifications

#**Key Metrics**
Total number of tenders
Total tender value (in Crores)
Tender stage distribution (count & value)
Number of buyers
Number of classifications

#**Key Insights**
Public Works Building and NH Department contributes the highest tender value
Open Tender method is most used, while Global Tenders (few in count) have very high values, contributing to skewness
Delays are mainly observed in Financial Bid Opening and Technical Evaluation stages
No strong correlation exists between tender value, duration, and number of bidders

#**Conclusion**
Tender value is concentrated in infrastructure projects and key buyers
Cancellations impact efficiency, while retenders are few
Delays are mainly due to process-related factors
Streamlining evaluation and tracking mid-process stages can improve performance
