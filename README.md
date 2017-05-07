# Python
Learn the high level programming language Python from the ground up with this helpful repository which covers everything between basic numerical operations right up to Data Structures and Algorithms. Commits welcome, must meet PEP8 coding standard.


### Installing Everything You Need

* Mac OSX
⋅⋅⋅ If you don't have a packager downloaded, now is the time to do it. Open your terminal and run:

⋅⋅⋅ `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

⋅⋅⋅ The script will explain what changes it will make and prompt you before the installation begins. Once installed, insert the Homebrew ⋅⋅⋅ directory at the top of your PATH environment variable. You can do this by adding the following line at the bottom of your ~/.profile ⋅⋅⋅ file:

⋅⋅⋅ `export PATH=/usr/local/bin:/usr/local/sbin:$PATH`

⋅⋅⋅ Now, we can install Python 3:
⋅⋅⋅ `brew install python3`

⋅⋅⋅ Once that's done, we need to install the Python package manager - pip. In your terminal, run the following four lines:

⋅⋅⋅ `curl -O http://python-distribute.org/distribute_setup.py`
⋅⋅⋅ `python distribute_setup.py`
⋅⋅⋅ `curl -O https://raw.github.com/pypa/pip/master/contrib/get-pip.py`
⋅⋅⋅ `python get-pip.py`

⋅⋅⋅ Now that we have the package manager, we can install thecoding standard we will be using for this repository - pep8.
⋅⋅⋅ To install pep8 run:
⋅⋅⋅ `pip install pep8`

* Linux
⋅⋅⋅ First of all check if your package manager, `apt-get` is updated by running the following command in your terminal:
⋅⋅⋅ `sudo apt-get update`

⋅⋅⋅ To install Python 3 on Linux run:
⋅⋅⋅ `sudo apt-get python3`

⋅⋅⋅ Once installed, install the Python package manager - pip. In your terminal, run the following lines:
⋅⋅⋅ `sudo apt-get install python-pip python-dev build-essential`
⋅⋅⋅ `sudo pip install --upgrade pip `

⋅⋅⋅ To install pep8 run:
⋅⋅⋅ `pip install pep8`
