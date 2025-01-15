#  Scientific publication with open source tools

This `github` repository will serve as the official resource for the NCSSM 2025 J-term course: *Scientific publication with open source tools*.

## Course description
Modern scientific research requires scientists to understand not only the content area they are studying, but to also have a strong understanding of the computing and data processing tools necessary to collect, analyze, and communicate their data and results. This course will teach students how to use open source tools in their scientific and technical workflows to conduct open source research and create open source publications.

At the end of the course, students will be able to install and run programs using their computer's terminal, use version control tools like github to effectively share code and data as part of a research team, produce rich interactive articles and websites based on their scientific and/or technical work, and much more. No previous experience with computing or scientific research required! The skills could be used to complete work in any technical field to produce transparent and reproducible outputs for everything from a physics lab report, to a journal ready chemistry paper. 

## Course Schedule
The course will run from Wednesday, January 8th - Friday, January 17th.

### Wednesday, January 8th: Why does academic publishing need some help?

#### Morning: Welcome and Getting Started (9am - 11am)
* Introductions (15 minutes)
* The need for open science ([slides](https://docs.google.com/presentation/d/1NzRybc7jhYV9KMoZM95LAieRbF_vXwBPM4LE_I2BVkA/edit?usp=sharing)) (30 minutes)
* **Activity** Comparing "traditional" scientific publication vs. "modern" scientific publication (45 minutes)
    * [ McAdam, Doug. “Recruitment to High-Risk Activism: The Case of Freedom Summer.” American Journal of Sociology, vol. 92, no. 1, 1986, pp. 64–90. JSTOR](https://www.jstor.org/stable/2779717)
    * [Speidel, L., Silva, M., Booth, T. et al. High-resolution genomic history of early medieval Europe. Nature 637, 118–126 (2025). https://doi.org/10.1038/s41586-024-08275-2](https://doi.org/10.1038/s41586-024-08275-2)
* Morning Wrap-up (15 minutes)

#### Mid-day indpendent work (11am - 2pm):
* Listen to [Freakonomics Radio: Why Is There So Much Fraud in Academia?](https://freakonomics.com/podcast/why-is-there-so-much-fraud-in-academia-update/) (76 minutes)
* Reflect on the podcast using the linked [Google Doc](https://docs.google.com/document/d/1hP5tdrW2RkEJGFLkyXaXCgG2uU5WEsh7kjQX7Fn8G8s/edit?usp=sharing) and be prepared to discuss in conversation this afternoon.

#### Afternoon (2pm - 4pm)
* **Activity**: Reflection and conversation on podcast (30 minutes)
* **Tool Exploration**: [Zotero](https://www.zotero.org/)
* **Tool Exploration**: [MyST](https://mystmd.org/) and [Curvenote](https://curvenote.com/)
* Window's Users Only: * **Activity**: Installing Linux on Windows (30 minutes)

#### Homework
* [Developing open source scientific practice (Millman & Perez)](https://berkeley-stat159-f17.github.io/stat159-f17/_static/ref/millman-perez.pdf) Read: Introduction and Chapters 1-2 (About 8 pages total)
* [Terminologies for Reproducible Research (Barba)](https://arxiv.org/pdf/1802.03311.pdf) Read: Pages 1-5, stopping at: Cataloguing the reproducibility literature

### Thursday, January 9th: Fundamentals of Computing

#### Morning: 9:30am - 11:30am
* **Activity**: Introduction to Command Line (45 minutes)
    * [Command Line Challenge](https://cmdchallenge.com)
    * [bashcrawl](https://gitlab.com/slackermedia/bashcrawl)
    * [Common terminal commands (realpython.com)](https://realpython.com/terminal-commands/#learn-basic-terminal-commands)
* Any troubleshooting from this morning's activities

### Mid-day independent work (11:30am - 2pm)
* On your own: [60 minutes: Duke Clinical Trials](https://www.youtube.com/watch?v=W5sZTNPMQRM)
* On your own: [The Importance of Reproducible Research in High-Throughput Biology](https://www.youtube.com/watch?v=8QJfNS7XXwA)

#### Afternoon: 2pm - 4pm
* Finding good data (15 minutes)
    * [Data is plural](https://www.data-is-plural.com/)
    * [Kaggle](https://www.kaggle.com)
    * [Gapminder](https://www.gapminder.org/)
    * [Project Gutenberg](https://www.gutenberg.org/)

* **Activity**: Figures from code vs. figures from spreadsheets
    * [Titanic Data Spreadsheet](https://docs.google.com/spreadsheets/d/1J3nt0aicpsDYe1ABQHpWlLmsqHcg6ut76d2h_9PKtBg/edit?usp=sharing)
    * [Titanic using Code](https://github.com/taylorgibson/jterm2025/blob/main/titanic-with-code.ipynb)
  
* Data Types and Programming boot camp (60 minutes)
  *  [10 minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html#merge)

#### Reading (on your own)
* [Developing open source scientific practice (Millman & Perez)](https://berkeley-stat159-f17.github.io/stat159-f17/_static/ref/millman-perez.pdf) Chapter 3 (About 8 pages total)
* [Reproducible Research (Yale Law School Roundtable on Data and Code Sharing)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5562471) (5 pages)

### Friday, January 10th: Getting Started with MyST

#### Morning: 9:00am - 11:00am
* Review the key elements of a research article: [Morganton Scientific Publication Criteria](https://docs.google.com/document/d/1xPeoVRL3Q2fjqln9qzmNNEMXuUUCTx2_N5ufKFvNakY/edit?usp=sharing)
* Install VSCode
    * [VSCode](https://code.visualstudio.com/) is a code editor that will be helpful when creating and editing files for your article / manuscript.
    * Install the MyST Markdown extension for nice color-coding of important sections of your article
* Create neccesary files for creating your article
    * `myst.yml`: The configuration file for your article
    * `article.md`: The text of your article
    * `analysis.ipynb`: A jupyter notebook for any data analysis and/or figure generation
    * `refs.bib`: A file for any references that do not have a DOI number assigned
* Understand key elements of a MyST `article.md` file:
    * Section headers
    * Figure call-outs
    * Tables
    * Citations

### Mid-day independent work (11am - 2pm)
* [Jupyter: Thinking and Storytelling With Code and Data (Granger and Pérez) (2021)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9387490) (7 pages)
* [Perspectives on Data Reproducibility and Replicability in Paleoclimate and Climate Science (Bush, et al.)](https://hdsr.mitpress.mit.edu/pub/dijwtzza/release/1) (About 16 pages)

#### Afternoon: 2pm - 4pm
* Independent time to make your first pass at completing a very basic version of your `article.md` file. At a minimum, you should have each of your sections created, with placeholder text in each section. Do not attempt to include figures, tables, or equations yet. Feel free to include citations that use DOI's now, but hold off on any citations that do not have DOI numbers assigned.

### Monday, January 13th: Citations and Markdown

#### Morning 9am - 11am
* How to cite sources that do not have a DOI using [BibTex](https://www.bibtex.org/)
    * [zbib](https://www.zbib.org): Great for quickly creating citations from DOI, ISBN, or URL
    * [Getting Started in MyST](https://docs.google.com/document/d/1sRM55nkGOBYGI5jPtTCev7H-DJISa1a4dTpN4LyGjfk/edit?tab=t.0#heading=h.k9g06w7v5unu): Contains additional examples of BibTeX citations.
* Review of using Markdown and Latex to format elements in your manuscript.
    * [LaTeX Cheatsheet](https://katex.org/docs/supported.html)
    * [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)

#### Mid-day independent work (11am - 2pm)
* [Better Poster Movement](https://www.youtube.com/watch?v=SYk29tnxASs)

#### Afternoon (2pm - 4pm): Office hours
* Meet with Mr. Gibson about your manuscript if you have any questions about it.
* Held in ETC-002 (the basement of the ETC building, down the hallway from the student center / Woolworth room

#### Reading (on your own)
* [Open Science by Design, Realizing a Vision for 21st Century Research (National Academies of Sciences, Engineering, and Medicine) (2018)](https://www.ncbi.nlm.nih.gov/books/NBK525417/pdf/Bookshelf_NBK525417.pdf) Chapter 4 (starts at page 124 in the PDF, which is page number 107 in the paper)


### Tuesday, January 14th: Creating figures
#### Morning 9am - 11am
* Learn how to create figures in a code notebook, and pull them into your article
    * Refresh: [10 minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html#merge)
    * [Referencing figures from notebooks](https://mystmd.org/guide/cross-references#targeting-cells)

#### Mid-day independent work (11am - 2pm)
* Work on your paper

#### Afternoon (2pm - 4pm): Office hours
* Meet with Mr. Gibson about your manuscript if you have any questions about it.
* Held in ETC-002 (the basement of the ETC building, down the hallway from the student center / Woolworth room

### Wednesday, January 15th: Github
#### Morning 9am - 11am
* Introduction to Git and Github (60 minutes)
    * What is github and why should you use it?
* Creating your github repository and setting up github pages
    * [Creating a key for your github account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) 
    * [How to setup a repository](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github#initializing-a-git-repository)
    * Don't forget to include `_build/`, `.ipynb_checkpoints/`, and (if on a Mac) `.DS_Store` in a `.gitignore` file!
    * [Setting up github pages with MyST](https://mystmd.org/guide/deployment-github-pages)
    * [Common `git` commands](https://docs.google.com/document/d/16NzI_AOenggZx7ygWzHMWhb0NL_sHhvNdnmxd5zBjyA/edit?usp=sharing)

#### Mid-day independent work (11am - 2pm)
* [Ten Simple Rules for Taking Advantage of Git and Github (PLOS Computational Biology)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004947)

#### Afternoon (2pm - 4pm): Office hours
* Meet with Mr. Gibson about your manuscript if you have any questions about it.
* Held in ETC-002 (the basement of the ETC building, down the hallway from the student center / Woolworth room
  
## Course Resources
* [Research software engineering in Python](https://merely-useful.tech/py-rse/getting-started.html)
* [UC Berkeley: Stat 159: Collaborative and Reproducible Data Science](https://ucb-stat-159-s22.github.io/site/overview.html)
* [Earth System Data Science in the Cloud](http://ncics-earth-system-data-science-b4e01a0.s3-website-us-east-1.amazonaws.com/module_0/overview/)
