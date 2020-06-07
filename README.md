Data of COVID-19 cases
----------------------

This repository aims to provide data of COVID-19 cases in readable format for scripts etc.

(Note: The accuracy of data depends on the sources. This repository only collects data available on the web.)

## Format
All data are saved in tab-separated value (.tsv).

## Example script
```python
import pandas as pd
import numpy as np

path = 'https://raw.githubusercontent.com/srifqi/covid19-data/master/'
csv_ = pd.read_csv(path + 'nation/ID.tsv', '\t')
data = np.array(csv_)
```
