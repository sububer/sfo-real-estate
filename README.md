# sfo-real-estate
San Francisco Real Estate Analysis For Rental Opportunities
FinTech Challenge 6

---

## Analysis 


See full analysis details in the notebook [san_francisco_housing.ipynb](./san_francisco_housing.ipynb)

#### DataSets



#### Assumptions


#### Summary




See full analysis details in the notebook [san_francisco_housing.ipynb](./san_francisco_housing.ipynb)

---

## Technologies

This challenge uses [python](https://www.python.org/) 3.7 and the following [built-in](https://docs.python.org/3/py-modindex.html) modules:
- [json](https://docs.python.org/3/library/json.html#module-json)
- [os](https://docs.python.org/3/library/os.html#module-os)

Additionally, it requires:
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)
- [numpy](https://numpy.org/)
- [geoviews](https://geoviews.org/)
- [hvplot](https://hvplot.holoviz.org/)


See [installation](#installation) below for specifics.

---

## Installation

You will need Python 3.7, that supports for this application to run. An easy way to install python 3.7 is to download and install [Anaconda](https://www.anaconda.com/products/individual). After installing anaconda, open a terminal/command-prompt, and setup a python 3.7 environment, and then activate it like so:

```
# create an anaconda python 3.7 environment
# name can be any friendly name to refer to your environment, eg 'dev'
conda create --name dev python=3.7 anaconda

# activating the environment
conda activate dev

# use pip to install the above modules, eg:
pip install python-dotenv
...etc...
```


---

## Usage

The analysis is presented within a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) notebook. To launch JupyterLab, from the root of this repo dirctory:

```
# within repo root 
$ jupyter lab --ContentsManager.allow_hidden=True
```
You can now open the notebook [san_francisco_housing.ipynb](./san_francisco_housing.ipynb) locally with JupyterLab.

---

## Contributors

[David Lopez](https://github.com/sububer)

---

## License

MIT