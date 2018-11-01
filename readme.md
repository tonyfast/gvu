
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/gitterHQ/gitter)[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/tonyfast/gvu/master)[__nbviewer__](http://nbviewer.jupyter.org/github/tonyfast/gvu/blob/master/readme.ipynb)[__github__](https://github.com/tonyfast/gvu)

#  [Project Jupyter and the rise of literate computing](https://www.cc.gatech.edu/hg/item/613206)

* By: Tony Fast [@docfast](https://twitter.com/DocFast)
* Thursday, November 1, 2018
* 11:30 am - 1:00 pm
* Location: Technology Square Research Building, 1st Floor Ballroom, Atlanta, Ga
* URL: Technology Square Research Building, 1st Floor Ballroom, Atlanta, Ga

Project Jupyter is a growing ecosystem of free, open source scientific software for literate and interactive computing.  Jupyter's Notebook, and related experiences, are becoming standard interfaces for scientists and engineers in physical and social sciences.  The notebook interface is impacting the broader landscapes of research, computing, and teaching where communicating data and code are essential; the stakeholders span industry, academia, and philanthropy.  

This talk will review the history of Project Jupyter as scientific software born from the Scientific Python (SciPy) community.  Since its inception, the community has extended Jupyter to work with over 50 different languages and provided new options for interactive development, research and presentation, including JupyterLab, the next generation of the Notebook.  In the broader open source community we find Jupyter tools for grading, batch processing, app development, documentation, tests, and even source code.

Notebook interfaces compose literate documents that provide the ability to share human and machine readable knowledge within organizations across diverse disciplines.  This talk will highlight recent case studies in Jupyter transforming classroom education, massive collaboration in physics, data-driven journalism, and the entire multimedia experience of learning.

## [Section 1](src/0.md.ipynb)
## [Section 2](src/2.md.ipynb)
## [Section 3](src/3.md.ipynb)

# Today we are going to talk about:

* I'm going to fanboy out about Project Jupyter.
* Adapting to open source software.
* Computational essays for people and computers.
* Sharing notebooks.
    [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/tonyfast/gvu/master)[__nbviewer__](http://nbviewer.jupyter.org/github/tonyfast/gvu/blob/master/readme.ipynb)[__github__](https://github.com/tonyfast/gvu)
* How word processing is evolving to include code and data.
    * Visualization is a subset of the document.

# About the presentation:

* This presentation is written in notebooks.
* The presentation in given in [__JupyterLab__](https://jupyterlab.readthedocs.io).
* All of the notebook can be read on [__nbviewer__](http://nbviewer.jupyter.org/github/tonyfast/gvu/blob/master/readme.ipynb) or [__github__](https://github.com/tonyfast/gvu).
* You can run these notebooks on [__MyBinder__](https://mybinder.org) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/tonyfast/gvu/master)
* Please feel free if you have an questions about the implementation of the presentation.  The  notebooks in this project can be viewed on nbviewer and binder.


```python
    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb
```
