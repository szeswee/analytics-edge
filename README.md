# analytics-edge

Contains course notes and implementation of assignments for **40.220 The Analytics Edge**

## Requirements

* [Jupyter](http://jupyter.org).
* A current [R installation](https://www.R-project.org).

## How to view results
1. Run the following commands in R console to install IRkernel (required for R support in Jupyter).
```R
install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))
devtools::install_github('IRkernel/IRkernel')
IRkernel::installspec()
```
2. Start the Jupyter server in the repository root with `jupyter notebook`.