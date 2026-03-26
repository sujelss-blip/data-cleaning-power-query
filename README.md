# 🧹 Data Cleaning Project – Power Query

## 📊 Overview

This project focuses on cleaning and transforming a raw transactional dataset using Power Query in Excel.

The dataset contained multiple data quality issues such as missing values, errors, and inconsistencies.

---

## 🧠 Data Cleaning Process

The following steps were applied:

* Removed rows with missing or invalid product names
* Eliminated errors and null values in critical columns (Quantity, Price, Date)
* Recalculated "Total Spend" using reliable fields (Quantity × Price)
* Standardized categorical fields (Payment Method, Location)
* Replaced inconsistent values (UNKNOWN, ERROR → null)
* Trimmed text fields to remove hidden spaces
* Created time-based columns (Year, Month)

---

## ⚙️ Tools Used

* Microsoft Excel
* Power Query

---

## 📈 Key Learnings

* Importance of handling null vs removing data
* Data consistency is critical for analysis
* Power Query enables reproducible data pipelines
* Cleaning data is a crucial step before visualization

---

## 📁 Files

* `cleaned_dataset.xlsx`

---

## 👤 Author

Sujel Sikaffi
