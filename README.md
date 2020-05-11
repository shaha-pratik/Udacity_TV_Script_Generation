# TV_Script_Generation_Pytorch_Udacity
This project is a part of deep learning nanodegree program at [Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Project Overview

In this project, you'll generate your own [Seinfeld](https://www.imdb.com/title/tt0098904/?ref_=nv_sr_srsg_0) TV scripts using RNNs.
You'll be using part of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) scripts from 9 seasons. The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

## Project Instruction

1. Clone the repository

```
https://github.com/shaha-pratik/TV_Script_Generation_Pytorch_Udacity.git
```
2. Install Anaconda or miniconda

This step is not mandotary but it will really good to understand and manage the enviroment in conda. Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers at https://www.anaconda.com/download/ and the installation instructions [here](https://docs.anaconda.com/anaconda/install/).

After that you can open the anaconda promt and create the virtual enviroment name `tv_script_generation` and activate as follow:

```
conda create --name tv_script_generation python=3.6
conda activate tv_script_generation
```

For conda cheatsheet can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)

3. Install [PyTorch](https://pytorch.org/) and [torchvision](https://pytorch.org/docs/stable/torchvision/index.html) as below

* Linux or Mac:
```
pip3 install torch===1.3.1 torchvision===0.4.2 -f https://download.pytorch.org/whl/torch_stable.html
```

4. After that to install [jupyter](https://jupyter.org/). The jupyter notebook is a web application that allows you to combine explanatory text, math equations, code, and visualizations all in one easily sharable document.
```
conda install jupyter notebook
```

5. Go to terminal and type
```
jupyter dlnd_tv_script_generation.ipynb
```
