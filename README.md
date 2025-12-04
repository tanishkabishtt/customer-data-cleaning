**🧹 Customer Data Cleaning Project
📌 Overview**
This project demonstrates the process of cleaning a raw customer dataset to make it analysis-ready. The raw data contained issues like inconsistent formatting, missing values, invalid entries, and duplicates. The cleaned dataset is standardized, consistent, and ready for analytics or dashboarding.

**🛠️ Cleaning Steps Performed**
Removed duplicates based on CustomerID

Fixed names by removing unwanted characters and extra spaces (e.g., rahul@@ → Rahul)

Handled missing values in Age, Phone, and JoinDate

Standardized city names (Delhi, Mumbai, Pune, etc.) with consistent casing

Converted JoinDate into proper YYYY-MM-DD format

Cleaned PurchaseAmount by removing invalid entries (e.g., ₹3000, not available)

Validated phone numbers by removing non-numeric or invalid values

**📊 Dataset Summary**
Raw Dataset: customer_raw_data.csv

Issues: messy names, invalid ages (e.g., twenty, 200, 0), inconsistent dates, duplicate records, invalid phone numbers

Cleaned Dataset: customer_cleaned.csv

Structured, consistent, and ready for analysis

Missing values left blank for transparency

**📂 Files Included**
customer_raw_data.csv — Original dataset with errors

customer_cleaned.csv — Final cleaned dataset

data_cleaning_customer_.ipynb — Python notebook with cleaning logic

README.md — Documentation of the cleaning process

🚀 **Next Steps**
Build a Power BI dashboard using the cleaned dataset

Add visual insights like customer distribution, revenue trends, and age demographics

