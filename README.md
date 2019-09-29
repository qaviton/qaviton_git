# Qaviton Git
![logo](https://www.qaviton.com/wp-content/uploads/logo-svg.svg)  
[![version](https://img.shields.io/pypi/v/qaviton_git.svg)](https://pypi.python.org/pypi)
[![license](https://img.shields.io/pypi/l/qaviton_git.svg)](https://pypi.python.org/pypi)
[![open issues](https://img.shields.io/github/issues/qaviton/qaviton_git)](https://github/issues-raw/qaviton/qaviton_git)
[![downloads](https://img.shields.io/pypi/dm/qaviton_git.svg)](https://pypi.python.org/pypi)
![code size](https://img.shields.io/github/languages/code-size/qaviton/qaviton_git)  
super light! super powerful! git wrapper  

## Installation  
```sh  
pip install --upgrade qaviton_git
```  

### Requirements
- git 2.16+  
- Python 3.6+ 

## Usage  

```python
from qaviton_git import Git

repo = Git.clone(
    path='', 
    url='https://github.com/qaviton/qaviton_git.git', 
    username='xxxx', 
    password='xxxx', 
    email='xx@x.x')
with open('newfile', 'w') as f: f.write('rock git hard')
repo.commit('new file').push()
```