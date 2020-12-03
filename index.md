---
title: "NIHR BRC Data Analysis Training - January 2021"
author: "Sheffield Bioinformatics Core"
output: 
  html_document: 
    toc: yes
    toc_float: yes
    css: stylesheets/styles.css
editor_options: 
  chunk_output_type: inline
---

<img src="images/logo-sm.png" style="position:absolute;top:40px;right:10px;" width="200" />


## Contact

web : [sbc.shef.ac.uk](https://sbc.shef.ac.uk)  
twitter: [SheffBioinfCore](https://twitter.com/SheffBioinfCore)  
email: [bioinformatics-core@sheffield.ac.uk](bioinformatics-core@sheffield.ac.uk)

## Dates

The course will comprise of five sessions

- Monday January 11th 13:00 to 16:00
- Wednesday January 13th 13:00 to 16:00
- Friday January 15th 13:00 to 16:00
- Monday January 18th 13:00 to 16:00
- Wednesday January 20th 13:00 to 16:00

Please only sign-up to the course if you are available on these dates, or prepared to devote time to review any sessions that you miss

# Session 1 - Data Organisation in Spreadsheets

## Overview

As a researcher, you will encounter research data in many forms, ranging from measurements, numbers and images to documents and publications. Whether you create, receive or collect data, you will certainly need to organise it at some stage of your project. This workshop will provide an overview of some basic principles on how we can work with data more effectively. We will discuss the best practices for research data management and organisation so that our research is auditable and reproducible by ourselves, and others, in the future.

## Software

You will need to install the OpenRefine software. This is free and available for Windows and Mac OSX. Download links are provided below:-

Windows Download
Mac Download

# Sessions 2,3,4 - Introduction to Data Manipulation and Visualisation using R

## Overview

As the data generated from high-throughput biological experiments increase in volume and become more complex, the ability to manipulate and visualise data is a highly-desirable skill in academia and industry. Whilst familiar tools such as Excel allow basic manipulations, they are often not scalable to larger datasets and are not ameanable to reproducible analysis. 

R is a highly-regarded, free, software environment for statistical analysis, with many useful features that promote and facilitate reproducible research.

In this course, we give an introduction to the R environment and explain how it can be used to import, manipulate and visualise tabular data. 

After the course you should feel confident to start exploring your own dataset using the materials and references provided. 

## Setup

These instructions are also described in a video:- [https://youtu.be/QIubJ8W8R4g](https://youtu.be/QIubJ8W8R4g)

1) First, install both R **and** RStudio for your operating system. 

### Windows

Install R by downloading and running [this .exe file](http://cran.r-project.org/bin/windows/base/release.htm) from CRAN. Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

### Mac

Install R by downloading and running [this .pkg file](http://cran.r-project.org/bin/macosx/R-latest.pkg) from CRAN. Also, please install the free [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download) 

### Linux

You can download the binary files for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install free [the RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download). 


  
2) Please download and extract (un-zip) [this zip file](CourseData.zip) into the directory on the computer that you wish to work in

3) Create an RStudio project using the menu **File -> New Project -> Existing Directory** and browse to the directory that you extraced the zip file to. Rstudio will refresh so that the working directory corresponds to the course data folder.

4) Type the following into the R console to install some extra R packages required for the workshop

```
install.packages("dplyr")
install.packages("ggplot2")
install.packages("readr")
```



**Mac Users may get the following error message when trying to install these packages**

```
xcrun error: inactive developer path (/Library/Developer/CommandLineTools), missing xcrun at:.....

```

If this is the case, you will need to follow the instructions from this link to install "Xcode"

[https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a](https://apple.stackexchange.com/questions/254380/why-am-i-getting-an-invalid-active-developer-path-when-attempting-to-use-git-a)

**Window users might get a message that Rtools is required. This shouldn't be neccesary, but you might need it for other packages. It can be installed here:-**

[https://cran.r-project.org/bin/windows/Rtools/](https://cran.r-project.org/bin/windows/Rtools/)


5) Check your installation. You can check everything is installed by copying and pasting this into the R console

```
source("https://raw.githubusercontent.com/sheffield-bioinformatics-core/r-online/master/check_packages.R")

```

Please watch this short presentation (<10 minutes) before attending the workshop

- [Course Introduction](https://www.youtube.com/watch?v=bb-qyh3c9vE)

## Course Notes

<!--+ [Introduction Slides](http://sbc.shef.ac.uk/r-online/intro_slides.html)
+ [Part 1](part1.nb.html)
+ [Part 2](part2.nb.html)
-->


# Session 5 - Statistical Analysis

## Overview

This course provides a refresher on the foundations of statistical analysis. The course is aimed at scientists at all levels – especially those whose formal education likely included statistics, but who have not perhaps put this into practice since. The focus of the course is on understanding the principles behind statistical testing, how to choose and execute the most appropriate test for your data, and how to interpret the result.

## Setup

Please download and unzip [this file](http://sbc.shef.ac.uk/stats-in-r/stats_course.zip)

Please watch these lectures before the workshop

- [Introduction](https://youtu.be/towMwBtg0KA)
- [Part 1](https://youtu.be/UXdsOBcsBjA)
- [Part 2](https://youtu.be/oDjOSV5yas4)
- [Part 3](https://youtu.be/uL6N07w3L18)

## Course Notes

<!--- [Notes and exercise solutions](https://sbc.shef.ac.uk/stats-in-r/practical.nb.html)
-->


