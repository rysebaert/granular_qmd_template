<h1> <img src="logos//granular.png"
  width="100"
  height="100"
  style="float:left;"
  hspace="20">
    Review data and methods : OpenStreetMap data and associated routing engine (OSRM) to produce novel data on rural areas in Europe 
</h1>

## Context

This repository aims at feeding the Horizon Europe project *Giving Rural Actors Novel data and re-Useable tools to Lead public Action in Rural areas project* ([GRANULAR](https://cordis.europa.eu/project/id/101061068)). 
More precisely, it corresponds to activities held in the Working Package 3 *Novel open data sources for rural areas*, task 3.1 (*Screen rural data sources and methods*) and 3.2 (*Explore options, performance and costs*).


## Abstract

This [review of the literature and data availability](https://rysebaert.github.io/granular_qmd_template/) aims at providing an overview of possible solutions and limitations for creating accessibility indicators at European context. 

Whatever the solution retained, computing accessibility indicators requires relevant origins / destination pairs and routing engines for computing travel-time indicators. It is afterward possible to propose a large set of indicators derived from these measures. 

The first part of the document presents at European scale the policy context and the main initiatives developed so far for proposing harmonized indicators on accessibility. The second one reminds the main issues to be considered when calculating accessibility indicators (origin-destination pairs, routing engines, accessibility indicators computation). The third section makes an overview of existing databases and possibilities that could be considered in a European context for the selection of origins / destinations pairs. The fourth part highlights existing solutions for routing engines according to several transportation modes (road, cycle, transport-transit). Finally, the last section discusses on possibilities offered in term of indicator creation when the travel time matrix is calculated with a case-study on hospitals in France. This case-study could be extended in a cross-border context to test this framework within GRANULAR activities. 

At the end, this report aims at providing a general research framework on the activities that will be held on task 3.3.1 of the GRANULAR project: Crowd-sources data based on OpenStreetMap.

## Repository organisation

This document is published using the [Quarto](https://quarto.org/) framework. It allows to publish high-quality articles, reports, books etc. in HTML format (among others). This repository is organised as follows: 

- The main Quarto document is available in the [index.qmd](https://github.com/rysebaert/granular_qmd_template/blob/main/index.qmd) file. 
- The deployed .html page corresponds to the [index.html](https://github.com/rysebaert/granular_qmd_template/blob/main/index.html) file. It uses the GitHub Pages to deploy the file on the Web. 
- The figures displayed in the document are available in the [figs](https://github.com/rysebaert/granular_qmd_template/tree/main/figs) folder. 
- Data used in the chunks of the .qmd file are available in the [data](https://github.com/rysebaert/granular_qmd_template) folder.
- Bibliography is stored in a BibTeX format in the [bib](https://github.com/rysebaert/granular_qmd_template/blob/main/bib.bib) file.
- Styles following the GRANULAR's graphical guidelines used by the .qmd file and deployed in the .html file are defined in the [styles.css](https://github.com/rysebaert/granular_qmd_template/blob/main/styles.css) file.  


## License
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)


<center>
<p float="center">
<img src="logos/riate.png" width="120" align="middle" hspace="80" vspace="80">
<img src="logos/cnrs.png" width="50" align="middle" hspace="80" vspace="80">
<img src="logos/uparis.jpeg" width="100" align="middle" hspace="80" vspace="80">
</p>
</center>
