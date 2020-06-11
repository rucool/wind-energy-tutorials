# Wind Energy Tutorials
Jupyter Notebook tutorials for plotting wind energy data.

[Rutgers University Center for Ocean Observing Leadership](https://rucool.marine.rutgers.edu/)


## Installation Instructions
Add the channel conda-forge to your .condarc. You can find out more about conda-forge from their website: https://conda-forge.org/

`conda config --add channels conda-forge`

Clone the wind-energy-tutorials repository.

`git clone https://github.com/rucool/wind-energy-tutorials.git`

Change your current working directory to the location that you downloaded wind-energy-tutorials. 

`cd /Users/lgarzio/Documents/repo/wind-energy-tutorials/`

Create conda environment from the included environment.yml file:

`conda env create -f environment.yml`

Once the environment is done building, activate the environment:

`conda activate wind-energy-tutorials`

To activate the jupyter notebook:

`jupyter notebook`

This will start a Jupyter notebook server in a browser window. You can then run and modify the notebooks.