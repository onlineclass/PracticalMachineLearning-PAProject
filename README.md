Practical Machine Learning - class Project
==========================================

This repository contains all the files created for the peer-assessed project of the Practical Machine Learning class.
The HTML-compiled version can be found at [https://onlineclass.github.io/PracticalMachineLearning-PAProject](https://onlineclass.github.io/PracticalMachineLearning-PAProject/index.html) URL.    
    
In order to compile the **index.html** file on a local computer you will have to download the content of this repository in a directory on your computer and then, from R, issue the following commands:    
* `library(knitr)` - loads the required **knitr** package    
* `knit2html("index.Rmd")` - compiles the **index.Rmd** file to markdown and then to HTML    
    
#### Performance

The three models trained and tested on the project's data sets (files *pml-training.csv* and *pml-testing.csv*) - **Gradient Boosting**, **k-Nearest Neighbors** and **Neural Networks** - will place a significant load on your local machine and can take a long time.    
    
On the machine on which **index.html** was generated (4 cores Intel Xeon CPU at 3.7GHz, Mac OS X 10.9), with 4 cores used via the **doMC** package, it took **472 seconds** to create the output file.    
    
You may have to change the **number of cores used by R** from the default 4 (see the `registerDoMC(4)` statement in the index.Rmd file) to a value suitable to your hardware platform.    

