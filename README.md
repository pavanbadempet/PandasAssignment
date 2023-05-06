# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?
A) dataFrame_name = pd.read_csv(file_name/file_path)
Q2. How do you check the data type of a column in a Pandas DataFrame?
A) dataFrame_name['column_name'].dtype
Q3. How do you select rows from a Pandas DataFrame based on a condition?
A) new_dataFrame_name = dataFrame_name[condition]
Q4. How do you rename columns in a Pandas DataFrame?
A) new_dataFrame_name = dataFrame_name.rename(columns={'old_column_name':'new_column_name'})
Q5. How do you drop columns in a Pandas DataFrame?
A) new_dataFrame_name = dataFrame_name.drop(columns=['column_name'])
Q6. How do you find the unique values in a column of a Pandas DataFrame?
A) unique_values = dataFrame_name['column_name'].unique()
Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
A) missingvalues = dataFrame_name.isna.sum()
Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
A) dataFrame_name = dataFrame_name.fillna(value)
Q9. How do you concatenate two Pandas DataFrames?
A) new_dataFrame_name = pd.concat([dataFrame1,dataFrame2])
Q10. How do you merge two Pandas DataFrames on a specific column?
A) dataFrame1.merge(dataframe2,on='column_name')
Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
A) dataFrame_name.grupby('column_name')['column_name'].agg(aggregation_function)
Q12. How do you pivot a Pandas DataFrame?
A) dataFrame_name.pivot(index='index_column', columns='columns_to_pivot', values='values_to_show')
Q13. How do you change the data type of a column in a Pandas DataFrame?
A) dataFrame_name['column_name'] = dataFrame_name['column_name'].astype('new_data_type')
Q14. How do you sort a Pandas DataFrame by a specific column?
A) dataFrame_name.sort_values(by='column_name', ascending=True/False, inplace=True)
Q15. How do you create a copy of a Pandas DataFrame?
A) new_dataFrame_name = dataFrame_name.copy()
Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
A) filtered_dataFrame_name = dataFrame_name[(condition1) & (condition2)]
Q17. How do you calculate the mean of a column in a Pandas DataFrame?
A) dataFrame_name = dataFrame['column_name'].mean()
Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
A) std_weight = dataFrame['column_name'].std()
Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
A) dataFrame_name['column_name'].corr(dataFrame_name['column_name'])
Q20. How do you select specific columns in a DataFrame using their labels?
A) dataFrame_name[['label1', 'label2', 'labeln']]
Q21. How do you select specific rows in a DataFrame using their indexes?
A) dataFrame_name.loc[index(es)]
Q22. How do you sort a DataFrame by a specific column?
A) dataFrame_name.sort_values('column_name')
Q23. How do you create a new column in a DataFrame based on the values of another column?
A) dataFrame_name['new_column_name'] = dataFrame_name['existing_column_name'].apply(function)
Q24. How do you remove duplicates from a DataFrame?
A) df.drop_duplicates()
Q25. What is the difference between .loc and .iloc in Pandas?
A) .loc is label-based indexing while .iloc is integer-based indexing