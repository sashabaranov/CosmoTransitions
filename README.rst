The CosmoTransitions package is a set of python modules for calculating properties of effective potentials with one or more scalar fields. Most importantly, it can be used to find the instanton solutions which interpolate between different vacua in a given theory, allowing one to determine the probability for a vacuum transition.

For more info, please read the documentation_. The current version is available via github_. Older versions of CosmoTransitions can be found at http://chasm.uchicago.edu/cosmotransitions .

 .. _documentation: http://clwainwright.github.io/CosmoTransitions
 .. _github: https://github.com/clwainwright/CosmoTransitions


Installation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To install CosmoTransitions, simply put the 'cosmoTransitions' folder somewhere in your path. Then from a python prompt one should be able to ``import cosmoTransitions`` and run the code. For examples, look in the ``test`` folder.

CosmoTransitions makes extensive use of numpy_ and scipy_, and the plotting functions use matplotlib_. It is recommended that users also install IPython_ for easier interactive use (IPython also contains an excellent html-based python notebook, which is very handy for organizing computational and scientific work). These packages can be installed separately (using e.g. easy_install_), or as part of a bundle (see the Anaconda_ distribution or the `Enthought Canopy`_ distribution).

CosmoTransitions was built and tested with Python v2.7.6, numpy v1.8.0, scipy v0.11.0, and matplotlib v1.2.0.

.. _numpy: http://www.numpy.org
.. _scipy: http://www.scipy.org
.. _matplotlib: http://matplotlib.org
.. _IPython: http://ipython.org
.. _easy_install: http://pythonhosted.org/setuptools/easy_install.html
.. _Anaconda: https://store.continuum.io/cshop/anaconda/
.. _`Enthought Canopy`: https://www.enthought.com/products/canopy/
