# Pasos a seguir para ejecucion del Jupyter Notebook.


## Setup del Anacoda env.
`conda create --name mineria python=10`
`conda activate`

## Establecemos el framework para Jupyter en el env.
`conda install -c anaconda ipykernel`
`python -m ipykernel install --user --name=mineria`


# Instalaciones necesarias.
`conda install -c conda-forge pandas`
`pip install Pillow`
`pip install pyparsing` <!-- resetear el kernel  -->
`!conda install -c conda-forge scikit-learn-extra`
`!conda install -c conda-forge wget`

> Finalmente, posicionarte en una carpeta en la que quieras trabajar.
`git clone https://github.com/varo6678/UOC_MasterDS_mineria_PRA2.git`

`jupyter notebook`

Y comenzar a trabajar.


