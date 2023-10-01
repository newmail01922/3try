Python Computing for Data Science
==============

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/profjsb/python-seminar/master)


#### A Graduate Seminar Course at UC Berkeley (AY 250) ####

##### Campbell Hall: Monday 4:10 - 7:00 PM SPRING 2022 #####

#### Synopsis ####

[Python](http://python.org) has become the *de facto* [superglue language for modern scientific computing](http://www.reddit.com/r/Python/comments/y9rku/astrophysicist_joshua_bloom_on_python_as_super/). In this course we will learn Pythonic interactions with databases, imaging processing, advanced statistical and numerical packages, web frameworks, machine-learning, and parallelism. Each week will involve lectures and coding projects. In the final capstone project, students will build a working codebase useful for their own research domain.

This class is for any student working in a quantitative discipline and with familiarity with Python. Those who completed the [Python Bootcamp](http://www.pythonbootcamp.info) or equivalent will be eligible. You should [follow the steps](https://sites.google.com/site/pythonbootcamp/preparation/software) to install the [Anaconda 3-2021-* distribution](https://www.anaconda.com/products/individual) as well as <code>git</code>.

#### Course Schedule ####

Date | Content | Reading | Leader
:--- | --------| ------- | ---: |
Jan 24 <font color="crimson">Online only</font> | **Numpy, Scipy, & Pandas** <br> [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/profjsb/python-seminar/master?filepath=DataFiles_and_Notebooks%2F03_Numpy_Scipy_Stats%2FNumpyIntro.ipynb)   | - scipy &sect;&sect; [1.3](http://www.scipy-lectures.org/intro/numpy/index.html), [1.5](http://www.scipy-lectures.org/intro/scipy.html), [2.2](http://www.scipy-lectures.org/advanced/advanced_numpy/index.html)<br>- [numpy](https://hal.inria.fr/inria-00564007/document)</br> - skim chap 4/5 of [McKinney](http://shop.oreilly.com/product/0636920023784.do?code=B2S3) | Josh
Jan 31	| **Data visualization** (Matplotlib, Bokeh, Altair)   | - Skim [Tufte's Visualization book](https://www.amazon.com/Visual-Display-Quantitative-Information/dp/0961392142)<br> - [colormap talk (Scipy 2015)](https://www.youtube.com/watch?v=xAoljeRJ3lU) | Josh
Feb 7  | **Application building and Testing** | None | Josh 
Feb 14  | **Parallelism** (asyncio, dask, ray, jax)  | None |Josh
Feb 21  | **Holiday** (no class) |  | 
Feb 28 | **Database interaction** (sqlite, postgres, SQLAlchemy),<br>**Large datasets** (xarray, HDF5) |  None | Josh
Mar 7  | **Machine Learning I** (sklearn: regression, classification; dask-learn, auto-ml) | None |Josh
Mar ~~14~~28	| **Machine Learning II** (keras [tensorflow]) | [Deep Learning with Keras](https://www.amazon.com/gp/product/1617296864/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=1617296864&linkCode=as2&tag=keras-io-20&linkId=aab94d0b04dccad37de3dffa22699e18) |Josh
Mar 21  | **Spring Break** |  | 
~~Mar 28~~  |  ~~Interacting with the world (requests, email, IoT/pyserial)~~	| ~~None~~ | ~~Josh~~
Apr 1 <br><font color="crimson">Friday 10-1pm</font>| **Web frameworks & RESTful APIs, Flask**		| None |  Josh
Apr 4  | No lecture |
Apr 11	|	**Bayesian programming & Symbolic math**	| [Probabalistic Programming eBook](http://nbviewer.jupyter.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter1_Introduction/Ch1_Introduction_PyMC3.ipynb)<br>install:<br>pip install pymc3| Josh
Apr 18	| **Image processing** (OpenCV, skimage)  | None | [Stefan van der Walt](https://github.com/stefanv)
Apr 25  | **Speeding it up** (Numba, Cython, wrapping legacy code) | None | Josh 
Onward   | final project work |
 

#### Useful Books ####

   - [Elegant Scipy](https://learning.oreilly.com/library/view/elegant-scipy/9781491922927/preface01.html) (UC Berkeley Library link)
       - [MyBinder Version](https://mybinder.org/v2/gh/elegant-scipy/notebooks/master?filepath=index.ipynb)
       - [Clean Notebooks](https://github.com/elegant-scipy/notebooks)
       
#### Sidebar Concepts ####

Throughout these lectures we will be peppering in sidebar knowledge concepts:
Python program to find the
# quotient and remainder
 
def find(n, m):
     
    # for quotient
    q = n//m
    print("Quotient: ", q)
     
    # for remainder
    r = n%m
    print("Remainder", r)
     
# Driver Code
find(10, 3)
find(99, 5)
  - Jupyter & JuypterLab
  - using git & github
  - Docker
  - Data science workflows
  - reproducible research
  - application building
  - debugging
  - testing

#### Workflow ####

Each Monday we will be introducing a reasonably self-contained topic with two back-to-back lectures. In between a short (~20 minute) breakout coding session will be conducted. Homeworks will require you to write a large (several hundred line) codebase.

Help sessions will be conducted interactively on the Piazza site for the course. There is also an in-person help session every TBD. Email [Josh](mailto:joshbloom@berkeley.edu) with any questions.

#### Contact ####

Email us at [ucbpythonclass@gmail.com](mailto:ucbpythonclass@gmail.com) or contact the professor directly ([joshbloom@berkeley.edu](joshbloom@berkeley.edu)).  You can also contact the GSI, Ellianna Abrahams, at ([ellianna@berkeley.edu](ellianna@berkeley.edu). Auditing is not permitted by the University but those wishing to sit in on a class or two should contact the professor before attending.
