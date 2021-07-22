# Data Science with Python
## Introduction
Hey Pal, this is the collection of tools, I have used for Data Science in Python for the past few years. I've added a short description, links and my recommendations for which I've found most helpful :)

## Core Software/Packages
- [Scipy](https://www.scipy.org/) - Scipy is a collection of data science tools, including [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/) and many more, each of which on their own is worth a look.
- [Numpy](https://numpy.org/) - Numpy is the standard mathematical numerical processing libary in Python, many many packages use this as a basis to build their packages on. Also many packages are mimicing it's API, e.g. [Pytorch](https://pytorch.org/), [Tensorflow](https://www.tensorflow.org/guide/tf_numpy), [Jax](https://jax.readthedocs.io/en/latest/jax.numpy.html).
- [Pandas](https://pandas.pydata.org/) - Similar to Numpy, Pandas is the defacto data table, dataframe package for Python. Definately worth getting familiar with Pandas, it will save you a lot of time in data manipulation. 

Recommendation: Highly recommend getting at least the basics of these packages, as they are invaluable in any project, and can always be used as a fallback if needed.

## Machine Learning and Deep Learning Packages
- [Scikit-learn](https://scikit-learn.org/stable/) - Part of Scipy, it is a collection of algorithms and methods used for ML, very useful. I would recommend taking a look, a very good fallback if other packages are missing a feature. I don't use it that much. Also has some good visualisation ability.
- [TensorFlow](https://www.tensorflow.org/) - TensorFlow is an open source machine learning framework, mainly made by *Google* that covers everything you could every want, from ML in research to production, from 1000 GPU training to inference on an edge device. 
    - It is very user friendly with its high level [Keras](https://www.tensorflow.org/api_docs/python/tf/keras) API.
    - TF is strongest in production, and is losing to PyTorch and Jax in Research.
- [Jax](https://jax.readthedocs.io/en/latest/notebooks/quickstart.html) - Jax is also an open source ML framework, used by *Google* in Research.
    - It is fairly new, so would not recommend for a beginner, but is gaining some traction in Research inside *Google* DeepMind.
- [PyTorch](https://pytorch.org/) - PyTorch is an open source ML framework, mainly used by *Facebook*. It covers almost as much as TensorFlow, but not quite, particularly in production. 
    - It is a little more difficult to learn compared to TensorFlow, as it has Keras. But is more rewarding if fully learnt.
    - If you do learn this, I would recommend [PyTorch Lightning](https://www.pytorchlightning.ai/), it is a high level API for PyTorch, like Keras is for TensorFlow.
    
Recommendation: I would use TensorFlow's Keras API if you want a quick solution, and would recommend learning PyTorch/PyTorch Lightning if you are going to use more long term ML research/applications.

## Plotting and Visualation Packages
- [Matplotlib](https://matplotlib.org/) - As Matplotlib is part of Scipy, it is pretty much the defacto for plotting and visualation tools in Python. So good to get the basics down.
    - Personally, I don't use it that much, and use [Plotly Express](https://plotly.com/python/plotly-express/) or [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html) built in plotting ability when I need to plot.
- [Pandas (plotting)](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html) - This is part of Pandas, and it very helpful as a quick plotting solution.
- [Plotly](https://plotly.com/python/plotly-express/) - Plotly is an open source plotting framework (it does have a paid version, but the free has always worked for me), that is great for quick visualisations
    - [Dash](https://plotly.com/dash/) - Part of Plotly, it is fantastic for real time data visualisation, and great for sharing data analysis with others. I've used to make several Dashboards that show data in real time to anyone that wants to view it.

Recommendation: For quick stuff, Pandas plotting tools are enough. For sharing and realtime, Plotly is great. For custom plots, Matplotlib is better.

## Image Processing
- [Matplotlib](https://matplotlib.org/) - Images can be viewed using Matplotlib and Numpy, but it isn't the easiest, definitely a fallback.
- [Pillow](https://python-pillow.org/) - Pillow is a high level framework for image processing and manipulation. It is the defacto image processing library for Python and is so high level that basics can be learnt in the best part of a day.
- [OpenCV](https://opencv.org/) - OpenCV is a low level image and computer vision framework. It covers far more than just image processing and manipulation, with its main application being Computer Vision, it can run CV neural networks and more. It is faster than Pillow, however it can be very difficult to use and learn, so only dive in if you really need the performance.

Recommendation: Pillow is king, unless you need extremely fast performance, in which case OpenCV with a lot of Googling XD.

## IDEs and QOL software
- [PyCharm](https://www.jetbrains.com/pycharm/) - Pycharm is a Python IDE that has more features than sense, all baked in. Mainly used for constructing programs, libraries, packages in Python. Has the best debugger I've found so far.
- [VSCode](https://code.visualstudio.com/) - VSCode is the jack of all trades and by default master of none. However, for any features it doesn't have someone has made a very high quality extension for it. Has a very good debugger and is generally lighter weight than PyCharm. An invaluable tool regardless of your use case.
- [Spyder](https://www.spyder-ide.org/) - Spyder, seems more aimed at data science than PyCharm or VSCode are, making it perfect for Research and data visualation.
- [Jupyter Notebook](https://jupyter.org/) - Jupyter Notebook are in a category of their own. If you want quick prototyping and want it to be explainable, wrapped up in a neat package, then Jupyter Notebook is the best you can get. Also the best tool for collaberating with others, as you can add images, notes, comments, graphs etc between and around your code.
    - [Google Colab](https://colab.research.google.com/) - An extension of the power of Jupyter Notebook, Google Colab by far the easiest way to do Data Science and ML in Python. You want access to a GPU, here you go! You want access to a TPU, say no more. You don't want to have to download 5GB of Python packages, they come preinstalled. Available anywhere anytime, and completely collaberative if needs be.
    - [Kaggle](https://www.kaggle.com/) - Kaggle has one of the largest collection of datasets in the world, and gets a special mention as it lets you get 30 hours of GPU and 30 hours TPU a week (good luck using all of that), while Colab sometimes doesn't give you a GPU.

Recommendation: Google Colab is invaluable as it covers all the basis for Data Science and ML. However, if Jupyter Notebooks aren't your thing, Spyder seems like the best IDE for Research, with VSCode being 2nd best. Defo worth looking at the basics of VSCode. 















