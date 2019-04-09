# HKU_Demo
Demo for the "Intro to Data Science and Machine Learning" Workshop on 9th April 2019

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
![tested-on-osx](https://img.shields.io/badge/Tested%20on-OSX-lightgrey.svg)

## How to Use this repo
1. Clone this repo:
```
$ git clone https://github.com/ohjho/HKU_Demo.git
$ cd HKU_Demo
```
2. install the requirements. Doing this inside a [virtualenv][url_virtualenv] is **highly recommend** and avoid [dependency hell](https://medium.com/knerd/the-nine-circles-of-python-dependency-hell-481d53e3e025).  
```
#---------------- optional ------------------
$ mkvirtualenv --python=`which python3` NameOfYourEnv
$ workon NameOfYourEnv
(NameOfYourEnv) $ pip freeze > uninstall.txt
(NameOfYourEnv) $ pip uninstall -r uninstall.txt -y
(NameOfYourEnv) $ rm uninstall.txt
#--------------------------------------------

(NameOfYourEnv) $ pip install -r requirements.txt
```
and just check and resolve any packages dependency issues if they show up under `pip check`. It should say `No broken requirements found.`  

3. Start Jupyter notebook
```
$ jupyter notebook
```
4. Have fun and go build some awesome projects! :surfer:

## Demo 1
[link to Jupyter Notebook][]

## Demo 2
[link to Jupyter Notebooks][demo2/]
