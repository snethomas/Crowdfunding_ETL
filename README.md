# Crowdfunding_ETL
Project 2 - Group 8
Contributors:
Beenish MM
Nnamdi Ezeoke
Sneha Thomas
Stephanie Loomer
Tekabe Fanta
--
We began by extracting and transforming the "crowdfunding.xlsx" (Resources Folder) Excel data to create a "category" DataFrame that has 2 columns (category_id, category) using Python and Jupyter Notebook. Similarly, we extracted and transformed the "crowdfunding.xlsx" (Resources Folder) Excel data to create a "subcategory" DataFrame that has 2 columns (subcategory_id, subcategory). Next,  a third campaign DataFrame was created via extraction and transformation of the "crowdfunding.xlsx" data this time with 14 columns. Finally, a fourth "contacts" DataFrame was created using Python dictionary methods, making sure to split the string at appropriate intervals. After creation, all DataFrames were exported to CSV files (contacts.csv, campaign.csv, category.csv, and subcategory.csv in the resources folder).  

Next, we went to work on creating and loading our database. We used Quick DBD (http://www.quickdatabasediagrams.com/) to create the schema used, and exported the schema query to pgadmin for SQL database creation. We imported all four CSV files into their proper tables, then ran select all statements on each to verify all data was imported correctly.
