## Basic Pandas commands
- `pd.read_csv()` = Reads a csv file
- `pd.read_excel()` = Reads an excel file
- `df.head(n)` = First n rows (default = 5)
- `df.tail(n)` = Last n rows (default = 5)
- `df.shape` = Tuyple with shape
- `df.drop_duplicates()` = Drop duplicate columns
- `df.rename(columns = {"c1" : "c2"}, inplace = True)` = Renames column `c1` to `c2`.
- `df.iloc[s1:s2]` = Prints head from index `s1` to `s2`.
- `df.groupby()` = Groups all the data as per the parameter given. Can also sum/series data for better visuals.