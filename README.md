# Syllabus
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/springcoil/probabilisticprogrammingprimer/master)

- Introduction to PyMC3
- What is MCMC and why should I care
	1. Why MCMC is needed
	2. A quick discussion of the difference between NUTS and M-H
	3. What is Metropolis-Hastings?
	4. What is NUTS


[!Link to course](https://www.probabilisticprogrammingprimer.com/) 
- Note: Data is fake data however it's inspired by some work done on a PPC campaign in the past. 

# Following the course on PyMC v3.8
The latest version of PyMC is v3.8.  There are significant API changes from previous versions.

See notebooks provided by Mark Farragher to follow the course on PyMC v3.8 under the `notebooks/pymc38` directory.

## Environment setup
Theano only supports [installation](http://deeplearning.net/software/theano/install.html) of requirements through `conda`.

Create an environment through these conda commands, using the dependencies in `requirements.txt`:

```sh
conda create -n ppp python=3.6
conda activate ppp
conda install --file requirements.txt
```

If you want to use an earlier version of PyMC, specify the version in the requirements file - e.g. `pymc3==3.6` for v3.6.
