# Horizon Graph

To see a explanation demo, please click this [Link](https://sysu-zjw.github.io/5005pre/)

### Usage 
Given a pd.DataFrame like:

| date | BTC | ETH | LTC | NEO | XRP |
| :---: | :---: | :---: | :---: | :---: | :---: |
|2017-06-06 | 2.089610e+09  |  7.415530e+08  |  3.210990e+08  |  5234170.0 |  132720000.0 |

```ruby
from HorizonGraph import *
fig=HorizonPlot(df,"date")
iplot(fig)
```

[<img src="https://github.com/sysu-zjw/MSBD-2018Fall/blob/master/img/HorizonGraph.png" width="300" height="170" align='center'>](https://sysu-zjw.github.io/5005pre/)
