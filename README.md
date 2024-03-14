# Resource Allocation

## Table of Contents

1. [Case Study](#introduction)
2. [Pre-requisites](#Prerequisites)
3. [Dependencies](#Depend)
4. [Metrics](#results)
5. [To-do](#todo)
6. [Contents of the Repo](#contents)

## Case Study <a name="introduction"></a>

A Supervision Manager has asked you to help in allocating scarce resources and identify which firms their team should focus on. Supervisory resources may be allocated according to the following characteristics: 

•	Firm size (i.e. the biggest firms need more attention) 
•	Changing business profile (are firms’ data changing substantially year-on-year?) 
•	Outliers from the norm (when looking at a single reporting period, does a firm deviate significantly from the average?) 


## Pre-requisites <a name="Prerequisites"></a>

- Python (DataFrames, Visualisations)
- Jupyter Notebook
- K-Means Clustering
- Microsoft Azure

## Dependencies <a name="Depend"></a>

- Python 3.10
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Metrics <a name="results"></a>

- Gross Written Premium (GWP) – total revenue written by an insurer. Equivalent of turnover for a non-insurance firm. 
- Net Written Premium (NWP) – GWP less reinsurance. NWP / GWP will show how much of the firm’s risk is being passed on to reinsurers.
- SCR coverage ratio – a measure of whether a firm is meeting its prudential capital requirements. Greater than 100% means the firm is holding enough capital to meet the requirement. The size of the buffer (i.e. surplus over 100%) can be important. 
- Gross claims incurred – a large cost to an insurer. Monitoring how these change over time for a firm is vital. 
- Net combined ratio – (incurred losses plus expenses) / earned premiums. This is a ratio that can indicate the profitability of a firm. If this is less than 100% it indicates a profit. 

## To-do <a name="todo"></a>

- Task I
	- Using the data provided, please analyse this data using python and produce a short report, including tables and charts, to highlight which firms should receive the most attention, according to the metrics above. 
- Task II
	- Please consider using relevant ML techniques to draw out further insights and present them as an annex to your report.
- Task III
	- The report is now required to be carried out using cloud technologies, can you describe the cloud tools and services and considerations, in particular using Microsoft Azure, to create an end-to-end data processing and analytics pipeline assuming data is batch processed daily?  Explain your decision


## Contents of the Repo <a name="contents"></a>

- Resource_Allocation.ipynb (Jupyter notebook with python code)
- Resource_Allocation.html (HTML version of the notebook)
- Dataset ((PRA)_(OFFG)_8350731_v_1_010242 - Analyst Data Science - Technical Assessment - Data.XLSX)