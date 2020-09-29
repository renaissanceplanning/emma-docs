Emma
========

Emma is a python-based toolkit to facilitate analysis of multimodal
accessibility for transportation planning and travel modeling applications.

Environment setup
-------------------
To use emma, start by configuring a development environment using Anaconda.
Open the terminal or Anaconda Prompt and enter:
::

    conda env create renaissanceplanning/emma

When conda finishes the installation, activate it as follows:
::

    conda activate emma

Additional packages may be installed in the emma environment as needed.
For example, Spyder or Jupyter may be desired for interactive programming
or notebook development using emma.

Package installation
---------------------
Clone this repository locally using git. In GitBash, for example, navigate
to an appropriate local folder where the repo will be cloned. Then type:
::

    clone http://github.com/renaissanceplanning/emma

This will save the emma package scripts locally. To make the package visible
in python (such that `import emma` works in any working directory), open conda
prompt in the emma/scripts folder.  With the `emma` environment active in
conda, type:
::

    python setup.py install

This is a very basic installation script, and more robust methods of
installing/updating emma may emerge over time.