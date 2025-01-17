# pygta-protocol-TA-PS1
pyglotaran STAR protocol for analysis of transient absorption spectra of photosystem I


## Scope
Global and target analysis of transient absorption spectra of photosystem I describing the protocol for Fig.1-4 and Fig.S1-5 the Cell Press paper DOI: [10.1016/j.isci.2023.107650](https://doi.org/10.1016/j.isci.2023.107650).


## Setup environment

There are many ways to setup a python environment. Here we use conda to create a new environment and install the packages needed to run the notebooks in this repository.

Create a new conda environment for this collection of packages

```shell
conda create --name pygta_protocol python=3.10
conda activate pygta_protocol
```

Now assuming we're in the right pygta_protocol environment, lets use pip to install the requirements from this repository

```shell
pip install -r requirements.txt
# installs pyglotaran, pyglotaran-extras and ipykernel
```
