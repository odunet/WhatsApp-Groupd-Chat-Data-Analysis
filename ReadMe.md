![GitHub Logo](/img/readimg.png)

# WhatsApp Chat Data Cleaning and Visualization Notebook
This script is written in python notebook. It is split into two scritps which perform the follwoing functions

**Cleanup_data.ipynb**
  - Take in raw whatapp chat date. This can be exported from whatsapp easily in txt format. [See here](https://android.stackexchange.com/questions/190505/how-to-export-convert-whatsapp-chat-to-pdf-excel-html)
  - Clean data using pandas and save clean data as *csv* 

**Manipulate_data.ipynb**
  - This is the script that helps to visualize the data using the Matplotlib library 
  - It is able to previde insights such as days of the week with the highest post

### Tech

Script uses widely available libraries
* Pandas
* Numpy
* Matplotlib
* Regular Expression

### Installation

This script is best run in a notebook environment e.g. [Jupyter Notebook](https://jupyter.org/).

Install the dependencies from the *Tech* list above.

```sh
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import re
from datetime import datetime
```

### Sample visualization 
This shows frequencies of chat over a period of 18 months with over 40,000 messages

![Sample Plot](/img/vis1.png)


![Sample Plot](/img/vis2.png)


License
----

MIT
**Free Script**