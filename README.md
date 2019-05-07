# Solutions to Mauricio Sacchi's Homework for LAPIS 2019

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/santisoler/lapis2019-sacchi-homework/master)

This repo contains a Jupyter notebook that performs the tasks left as homework by
Mauricio Sacchi on the LAPIS 2019 School.

It contains:

- `Solution to Homework.ipynb`: Jupyter notebook with the solutions to the homework.
- `environment.yml`: Configuration file for creating Anaconda environment.

The `Solution to Homework.ipynb` notebook has been written by
[Santiago Soler](https://github.com/santisoler) and
[Sebastian Correa-Otto](https://github.com/sacaliza)
in order to pass the LAPIS 2019 assignments.


## How to run?

### Use Binder

The easiest way to run the notebook is through [Binder](https://mybinder.org).
Just follow
[this link](https://mybinder.org/v2/gh/santisoler/lapis2019-sacchi-homework/master)
and wait until Binder loads the notebook.

### Download the repo and run it locally

You'll need a Python distribution to make it run with the following dependencies:
- numpy
- scipy
- matplotlib

The easiest way to get Python and all of these dependencies installed is through
[Anaconda](https://www.anaconda.com/).
Download the latest Anaconda 3 distribution for your OS.

Then clone the repo:

```
git clone https://github.com/santisoler/lapis2019-sacchi-homework
```

or
[download it](https://github.com/santisoler/lapis2019-sacchi-homework/archive/master.zip)
as a zip file.

Change your working directory to the cloned repo and create the conda environment to get
all the dependencies:
```
cd lapis2019-sacchi-homework
conda env create
```

Once all the packages have been downloaded and installed, activate the repository:
```
conda activate lapis2019
```

Finally, start a Jupyter Notebook kernel:
```
jupyter-notebook
```
This will open a new page on your web browser where you will be able to find the
`Solutions to Homework.ipynb` notebook.
You'll be able to open it and run any cell.
If you want to reproduce our results, run all cells in order.


## License

All code is licensed under the MIT License.

Copyright (c) 2019 Santiago Soler, Sebastian Correa-Otto

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
