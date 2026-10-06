# SWYNEX-Data-Cleaning
Data Cleaning and preparation of a cafe sales dataset using Microsoft Excel.

Dataset Overview
- Worked on a Cafe Sales dataset containing 10,000 transaction records and 8 columns.
- Kept the Raw Data and Clean Data separately for clear comparison and verification.
  
  Issues Found
- Duplicate records were checked and no duplicates were found.
- Missing and invalid entries such as blank cells ERROR and UNKNOWN values were found across multiple columns.
- Some transaction dates were not in a consistent order and some dates were missing or invalid.

   Cleaning Steps
- Filled missing Item and Price Per Unit values using related information from the dataset wherever they could be logically determined.
- Recalculated missing or invalid Quantity values using Total Spent ÷ Price Per Unit where the required values were available.
- Recalculated missing or invalid Total Spent values using Quantity × Price Per Unit.
- Standardized unavailable Payment Method and Location values as Missing.
- Organized valid transaction dates into a consistent sequence and marked dates that could not be determined reliably as NA.

   Result
- The dataset was cleaned and prepared for further analysis while keeping the original data unchanged for reference.
- 6,763 rows contained at least one modification.
- 9,620 cells were modified during the cleaning process.
- Duplicate check completed with no duplicate records found.

  Tools Used
- Microsoft Excel
- Excel formulas and data-cleaning techniques for validation calculation and standardization.
