# Getting Started with Data Science Tools

These items are included in the Data Science prework to help students prepare for the first day of class.
- Github Account
- Installations
- Syntax Practice

### Github
1. Create a Github account, if you don't already have one.
2. Email our github user name so we can give you read access to our course repository.
3. Accept the invitation and navigate to the course repo homepage.
4. Clone the course repo to your local computer.


### Installations
Please follow the installation instructions below.

#### Just For Windows Users - Optional
If you are running Windows, you will need to install a virtual machine that runs Linux. We're recommending that you use [VirtualBox](https://www.virtualbox.org/wiki/Downloads) with [Ubuntu](http://www.ubuntu.com/). Here's how to get started:

1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
    - Make sure to also install the "Extension Pack" for your version!
2. Download our [Ubuntu starter image](https://www.dropbox.com/sh/3mp1p3av2k6be4y/AADstHqUMSPRyYPWuk_C3XAJa?dl=0) labeled "For PCs only"
    - You'll need at least 2-3 gbs of free disk space.
3. Open VirtualBox and import the image
4. Double-click the Virtual Machine on the left; the password is "**ilovedatascience**"

#### For everyone

1. Install [Python 2.7](https://www.python.org/downloads/)
   - Make sure to install version 2.7, NOT Python 3.

2. Install [Anaconda](https://www.continuum.io/downloads)
   - Follow the installation instructions for your computer (e.g. “Mac Install”). 
   - Test that Anaconda and Python were installed correctly. For example, on a Mac you can by open a Terminal window (or the Anaconda Launcher app on your desktop) and type `jupyter notebook`. If successful, in a few moments, your browser should open to a window titled "Jupyter."

3. Check the installation and versions of *all* the python libraries by running the `starter-code/install-test.ipynb` jupyter-notebook:

    - Open a terminal, navigate to your local version of `DAT-NYC-43/classes/lesson-01/code/starter-code`

         ```bash
         $ cd <your 'clone' location>/DAT-NYC-43/classes/lesson-01/code/starter-code
         ```
    - Run the `jupyter notebook`
 
         ```bash
         $ jupyter notebook
         ```

    - Open the notebook by selecting the notebook file
    - From the `Kernel` menu select `Restart & run all`

### Start Practicing
Review the following resources as an introduction to some commonly used concepts and tools.

1. Complete Codecademy's free ["Learn Python"](https://www.codecademy.com/learn/python) course to practice your Python syntax. Pay close attention to lists, dictionaries, and functions.
   - Bonus Option: Check out [Learn Python the Hard  Way](http://learnpythonthehardway.org/book/) and work through exercises 1-10.

2. Review our [Command Line](http://generalassembly.github.io/prework/cl/#/) tutorial to familiarize yourself with basic Terminal commands. Pay particular attention to folder navigation and file creation.
   - Bonus Option: Run through these additional exercises from [Learn Command Line the Hard Way](http://cli.learncodethehardway.org/book/).

3. Read through this [10 minute guide to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html) to learn about a popular library used for data analysis that we will be using in this course.
   - Bonus Option: Practice your Python by working through [Project Euler's computational problems](https://projecteuler.net).

