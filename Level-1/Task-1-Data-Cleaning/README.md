# Task 1 : Data Cleaning & Preprocessing  

## Objective  
- Load and explore the dataset using **pandas**  
- Audit data quality (missing values, duplicates, data types)  
- Detect and remove outliers in selected features (CRIM, ZN, B, LSTAT, MEDV)  
- Apply feature scaling with **StandardScaler**  
- Export the cleaned dataset for further analysis  

## Workflow  
1. Imported the raw dataset (space‑separated, no header) and assigned descriptive column names.  
2. Performed initial inspection:  
   - No missing values detected  
   - No duplicate rows found  
3. Outlier treatment using the **IQR method** on selected columns.  
   - Dataset reduced from 506 → 297 rows after cleaning  
4. Standardized all numerical features to ensure uniform scale.  
5. Saved the processed dataset as `Cleaned_Dataset.csv`.  

## Tools & Libraries  
- Python  
- Pandas & NumPy  
- Scikit‑learn (StandardScaler)  
- Matplotlib & Seaborn  

## Repository Contents  
- `Task1_Data_Cleaning.ipynb` → Jupyter Notebook with full code  
- `Cleaned_Dataset.csv` → Final cleaned dataset  
- `README.md` → Documentation of the process  

## Author  
Rawan Mahmoud Kamal
Data Analysis Intern – Codveda Technologies  
