# rm-evaluation

## Project objective:
### Explore and predict, if possible, the best combination of ingredients for the manufacture of inorganic colored pigments to produce within customer specifications .

<br/>

### Brief explanation of "color numbers"
<p>"Color numbers" is a generic term for what is specifically known as "Lab" or CIELab values. Essentially, CIELab values are a way to plot colors on a 3-dimensional plane.  The "L" value represents a position on the vertical axis, the "a" value represents a position on a horizontal axis and the "b" value represents a position on another horizontal axis that is perpendicular to the "a" axis. 
For more information on CIELab values you can check out this short [article](https://www.xrite.com/blog/lab-color-space). </p>

## How the project meets the Feature List requirements
### Feature 1:
- [x] Read in Excel files

### Feature 2:
- [x] Join/Merge files with pandas

### Feature 3: 
- [x] Matplotlib/seaborn visualizations

## Setting up the environment
<p>If using Anaconda then the virtual environment used for this project can be copied from the environment.yml file.

Once the repo has been cloned and the Anaconda Prompt is within the cloned repo directory the following code can be placed in the prompt to copy the conda virtual environment.</p>

```
conda env create -f environment.yml
```

<p>After the virtual environment has been copied it can be activated with the following code.</p>

```
conda activate rm_evaluation
```

<p>Once inside the virtual environment, open jupyter notebook with the following command in the Anaconda Prompt</p>

```
jupyter notebook
```
<p>To run the program open the main.ipynb file. One thing to note is that there is one cell that requires user input so choosing 'Run All' cells will stop execution at that cell until the appropriate user input is entered.</p>

<p>
If using a python virtual environment please install the following packages with pip or whatever means you install packages.
</p>

```
  python=3.10
  matplotlib
  seaborn
  pandas
  jupyter
```
<p>The program is in a jupyter notebook named main.ipynb </p>