# PHYS4606 - Mathematical and Computational Methods for Physics
This repository contains material for the class PHYS4606 - Mathematical and Computational Methods for Physics. We will use Python and Mathematica in this class. Python is free and there is a free Mathematica license for Northeastern students.

## Software installation (Mathematica)
To access Mathematica follow <a href="https://service.northeastern.edu/tech?id=kb_article_view&sysparm_article=KB0012562&sys_kb_id=ff8b3ef6874771d43b170e96cebb3518&spa=1" target="_blank">these instructions</a>.

## Software installation (Python)

### Option 1: Local software installation

#### For Linux and Mac users:
1.) Open a terminal:

  On Linux press: Ctrl + Alt + T
  
  On Mac press: command+space, type ``terminal``, press enter
  
2.) Create a virtual environment: execute the command

```python3 -m venv ~/venv-phys4606```

3.) Activate the environment (needs to be done every time):

```source ~/venv-phys4606/bin/activate```

4.) Update the package manager (needs to be done only once):

```pip install --upgrade pip```

5.) Install some packages (needs to be done only once):

```pip install numpy matplotlib jupyter notebook pandas joblib scipy sympy```

7.) To open jupyter in your default browser execute:

```jupyter notebook```

#### For Windows users:
1.) Open a terminal: Press: Windows key + x, select Windows Terminal (Admin)

2.) Download python (skip if you already have python)

```winget install python.python.3.9```

3.) Update the package manager (needs to be done only once):

```pip install --upgrade pip```

4.) Install package for virtual environment (needs to be done only once):

```pip install virtualenv```

5.) Create a virtual environment: execute the command (replace ``C:\Path\To\Python\`` with the path into which you installed Python)

```virtualenv --python C:\Path\To\Python\python.exe venv-phys4606```

6.) Activate the environment (needs to be done every time):

```.\venv-phys4606\Scripts\activate```

7.) Install the required packages (needs to be done only once):

```pip install numpy matplotlib jupyter notebook pandas joblib scipy sympy```

8.) Open jupyter in your default browser:

```jupyter notebook```

### Option 2: Google Colab (Python online)
This option requires a google account. Once you have one setup, follow the steps at <a href="https://colab.research.google.com/" target="_blank">https://colab.research.google.com/</a>.



