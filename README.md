# Requirments

* Step 1: If you are using `conda`, it is recommended to set up a new environment with the command `conda create -n <env name> python=3.10`. Then use `conda activate <env name>` to enter into the new environment. 

    * Note: If you don't want to create a new environment, use the command specified in Step 2 directly to install all dependent packages under your current environment.

* Step 2: Once the new environment is activated, use the command `pip install -r requirements.txt` to install all dependent packages of this project. 


# Serve the dashboard

To serve the dashboard locally, use the command: `panel serve dashboard.ipynb --show`. It will automatically open a window in the browser. This usually take less than 30 seconds to download remote dataset, as well as packing new packages.

![wUyWuhbTLk4HRSX](https://s2.loli.net/2022/11/03/wUyWuhbTLk4HRSX.png)

# Data Sources

1. https://github.com/owid/covid-19-data/tree/master/public/data
2. https://exploratory.io/map