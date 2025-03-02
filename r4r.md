---
layout: page
title: "R4R: reproducibility for R"
permalink: /r4r
---


# R4R

R4R is a reproducibility tool for R. 

It traces the execution of a R script, or a Rmarkdown document, detects the R *and* the system dependencies, and then prepares a minimal Docker image with the software and data dependencies that you can run your R code in and get the same result as on your machine.


It currently only supports Debian and Ubun Linux distributions.
