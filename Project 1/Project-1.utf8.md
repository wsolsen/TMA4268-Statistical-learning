---
subtitle: "TMA4268 Statistical Learning V2021"
title: "Compulsory exercise 1: Group 4"
author: "NN1, NN2 and NN3 (full names of all group members)"
date: "08 februar, 2021"
output: 
 # html_document
  pdf_document
---
  







For some problems you will need to include some LaTex code. Please install latex on your computer and then consult Compulsory1.Rmd for hints how to write formulas in LaTex. 

An example:

$$Y_i  = f(x_i) + \varepsilon_i \ ,$$

Or the same formula $Y_i  = f(x_i) + \varepsilon_i$ in-line.


# Problem 1

## a)

## b)

## c)


```r
id <- "1X_8OKcoYbng1XvYFDirxjEWr7LtpNr1m" # google file ID
values <- dget(sprintf("https://docs.google.com/uc?id=%s&export=download", id))

X = values$X
dim(X)
```

```
## [1] 100  81
```

```r
x0 = values$x0
dim(x0)
```

```
## [1] 81  1
```

```r
beta=values$beta
dim(beta)
```

```
## [1] 81  1
```

```r
sigma=values$sigma
sigma
```

```
## [1] 0.5
```

 

# Problem 2

## a) 


