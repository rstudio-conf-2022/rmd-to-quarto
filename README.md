From R Markdown to Quarto
================

### rstudio::conf 2022

#### Teaching Team

Andrew Bray
Rebecca Barter
Silvia Canelón
Christophe Dervieux
Devin Pastoor
Tatsu Shigetu

-----

:spiral_calendar: July 25 and 26, 2022  
:alarm_clock:     09:00 - 17:00  
:hotel:           National Harbor 12/13
:writing_hand:    [rstd.io/conf](http://rstd.io/conf)

-----

## Overview

This workshop is designed for those who want to take their R Markdown skills and expertise and apply them in Quarto, the next generation of R Markdown. Quarto is an open-source scientific and technical publishing system that offers multilingual programming language support to create dynamic and static documents, books, presentations, blogs, and other online resources. In this workshop you will learn how to apply your reproducible authoring skills to the Quarto format and learn about new tools and workflows for authoring with Quarto in RStudio. You will learn to create static documents, to add interactivity to them with Shiny and htmlwidgets, and to create presentations in various formats such as reveal.js, beamer, and pptx. The workshop will also introduce you to Quarto projects which you can use to build websites and write blogs and books. Finally, you will learn various ways to deploy and publish your Quarto projects on the web. Independent modules will also highlight authoring in Quarto with Jupyter and VS Code as well as other text editors.

## Is this course for me?

This course will be appropriate for you if you answer yes to any of these questions:

Have you authored R Markdown documents and are you interested in migrating your workflow to its successor format, Quarto?

Are you interested in exploring the wide spectrum of documents that can be produced with Quarto, including static documents, websites, and slides?

## Prework

Each session of the workshop features exercises that will learn Quarto by doing. To prepare, please install the following on your machine:

- If you haven't already, please [sign-up](https://happygitwithr.com/github-acct.html) for a free GitHub account.
- Install latest version of [RStudio](https://www.rstudio.com/products/rstudio/download/#download), v2022.07.0-548 or later
- Install latest version of [Quarto](https://quarto.org/docs/get-started/) (v1.0.36 or greater)
- After installing Quarto, open the terminal in RStudio and:
  - See [this guide](https://support.rstudio.com/hc/en-us/articles/115010737148-Using-the-RStudio-Terminal-in-the-RStudio-IDE) for details on using the terminal
  - Install/Update TinyTeX for PDFs with `quarto install tool tinytex`
  - Install/Update Chromium with `quarto install tool chromium`
- Ideally upgrade/use to R 4.1 or R 4.2
- Install these R packages:
  
  ```{r}
  #| eval: false
  #| echo: true
  pkg_list <- c("tidyverse", "quarto", "rmarkdown", "palmerpenguins")
  install.packages(pkg_list)
  ```

## Schedule

### Day 1

| Time          | Activity         |
| :------------ | :--------------- |
| 09:00 - 10:30 | Welcome to Quarto        |
| 10:30 - 11:00 | *Coffee break*   |
| 11:00 - 12:30 | Polishing Documents       |
| 12:30 - 13:30 | *Lunch break*    |
| 13:30 - 15:00 | Computation   |
| 15:00 - 15:30 | *Coffee break*   |
| 15:30 - 17:00 | Projects and Publish        |

### Day 2

| Time          | Activity         |
| :------------ | :--------------- |
| 09:00 - 10:30 | Presentations        |
| 10:30 - 11:00 | *Coffee break*   |
| 11:00 - 12:30 | Websites       |
| 12:30 - 13:30 | *Lunch break*    |
| 13:30 - 15:00 | Workshop Projects      |
| 15:00 - 15:30 | *Coffee break*   |
| 15:30 - 17:00 | The Future of Quarto        |

## Instructor

Andrew Bray is an Associate Teaching Professor in the Department of Statistics at UC Berkeley where he develops and teaches courses in statistics and data science. His research interests include statistical computing, data privacy, and applications of statistical models to environmental science. He was previously an Associate Professor of Statistics in the Department of Mathematics at Reed College and an NSF Five Colleges postdoctoral fellow in western Massachusetts.

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
