<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">NUS Module Scripts</h1>

  <p align="center">
    This is a repository where I keep all the modules I have written code for to automate processes. 
    <br />
    <br />
  </p>
</p>

The pandemic meant that a lot of my modules had online exams that were open-book, open-internet, open-everything. I saw the opportunity to automate manual calculations, from basic things like symbolic/numerical integration and statistical tests to more complex ones like random forest/linear regression models and dimensional analysis. 

In these repositories I have included code I have written as Jupyter Notebooks, and my cheatsheets/notes for the module. Hopefully, this helps someone out there.

## Table of Contents

- [Modules](#Modules-)
- [Set up](#Set-up-)

## Modules
1. EE2211 Introduction to Machine Learning
This module covers the basics of machine learning. It covers basic data engineering techniques and fundemental supervised and unsupervised machine learning algorithms, such as polynomial regression, random forest models and fully connected neural networks.

I implement all the models taught from scratch as we were expected to do them by hand. I also implement other relevant calculations like calculating performance metrics, probability/statistics, etc. 

2. ME2112 Strength of Materials
This module introduces one to the basics of stress and strain in materials. It covers statics analysis, stress and strain, beam bending and torsion. 

Calculating the stress and strain arising from beam bending and torsion requires a lot of tedious integrals, so I automated them using SymPy. It helped me to finish my final in 30 minutes. I got an A+, haha. 

3. ME2134 Fluid Mechanics I
This module covers the basics of fluid mechanics, from fluid statics to dynamics and pipe flow. 

Calculation of values in static and dynamic fluid problems involved a lot of tedious integrals, so I automated it using SymPy. Dimensional analysis is algorithmic in nature but tedious, so I automated it using Excel. 

4. ME2162 Manufacturing Processes
This module covers the basics of manufacturing practices, from machining to metal working and 3D printing. A lot of the calculations were algorithmic in nature, so I automated them to avoid careless mistakes.

5. ST1131 Introduction to Statistics and Statistical Computing 
This module introduces one to the basics of probability, and focuses heavily on statistical computing in R. We were expected to learn R on our own and be able to process a large dataset given to us in some file format in the final and perform calculations based on it. 

I picked up R and prepared a simple notebook to streamline my workflow. 

6. ST2334 Probability and Statistics
This module introduces students to basic probability theory and statistical inference. Topics include basic concepts of probability, conditional probability, independence, random variables, joint and marginal distributions, mean and variance, some common probability distributions, sampling distributions, estimation and hypothesis testing based on a normal population.

We were expected to perform calculations with these tests by hand using statistical tables, but excel, or R were allowed. We were not allowed to use Python. So, for the statistical tests, I implemented all of them with R's default library, but used RSymPy to automate symbolic calculations. 

## Set up
For easy annotation I wrote these scripts with Jupyter notebooks, which you will need. They are written in Python and use a mix of modules, such as numpy, matplotlib, sklearn, etc. All of these come with the [Anaconda Package](https://www.anaconda.com/), and I recommend you install it for ease of use. Use Jupyter Notebook in the Anaconda Navigator to open them.
