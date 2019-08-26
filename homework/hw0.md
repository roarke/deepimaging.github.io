1. Installing Python:
Download the latest version of python3: `https://www.python.org/downloads/`
Install juypter by running these commands in your shell:
```sh
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```
 - MacOS users, you can find your terminal by typing `terminal` in your search bar.
 - Windows users, you should be able to use powershell. For long term happiness though, install the bash shell: [linux - How to enable Bash in Windows 10 developer preview? - Stack Overflow](https://stackoverflow.com/questions/36352627/how-to-enable-bash-in-windows-10-developer-preview)

 Alternatively use [Anaconda](https://docs.conda.io/en/latest/miniconda.html) for Python 3.7 and then run `conda install jupyter`

2. If for some inexplicable reason you don't have a Gmail account, make one.

3. Login to [Google Colab](https://colab.research.google.com), start a new python3 notebook

4. Make sure that the following commands run without error and return `'1.14.0'`
```sh
import numpy as np
import tensorflow as tf
import sklearn as skl
import matplotlib.pyplot as plt
import scipy as sp
tf.__version__
```


5. Take this survey: [Homework 0: Survey](https://goo.gl/forms/hV8rUMVzjIxEX3S73)

### If you have any issues, we will find time to debug during our zeroth TA session Monday or Wednesday (depending on your section)
---------------------

## After the zeroth TA session, you should do the following:
### Feel free to try on your own before the TA session if you are comfortable!
 - Introduce yourself by writing in the `homework_0.ipynb` file
 - Spin up a small google cloud platform instance with a publicly accessible IP address.
 - Submit your homework here: https://goo.gl/forms/NS5tp08lcq6OjNst1
