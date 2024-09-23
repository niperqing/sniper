# sniper
初学 开源 python
import numpy as np
import pandas as pd

print('>'*100+'001:从excel表导入数据')
df = pd.DataFrame(pd.read_excel(
    'excel/resource/001_excel.xlsx', sheet_name='Sheet1'))
print(df)
print()

print('>'*100+'002:从csv导入数据')
df2 = pd.DataFrame(pd.read_csv('excel/resource/001_csv.csv', header=0))
print(df2)
