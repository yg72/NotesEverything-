**读取excel文件画图**
https://www.gairuo.com/p/pandas-read-excel

import pandas as pd

df = pd.read_excel('setting.xls').to_numpy()
print(df.shape)

**画subgraph**

fig, ((ax1, ax2), (ax3, ax4)) = plt.subplots(2,2,figsize=(12,12))  # figsize 重要

ax1.scatter(x, 2708-y, s=0.1)

**画热力图**

数据是pandas dataframe

dataframe.to_numpy().tolist()

colormap

https://mp.weixin.qq.com/s?__biz=MzUwOTg0MjczNw==&mid=2247484329&idx=1&sn=20ec36f7f5077221671b32d47c3412c8&chksm=f90d47f7ce7acee11449c5584a11a020cf05c27f7a60b9357bbdc35181cc7e8420c594d09fc5&scene=158#rd

**数据转换**

tensor to numpy a.numpy()

numpy to tensor torch.from_numpy(a)

list to numpy  np.array(a)

numpy to list x.tolist()



