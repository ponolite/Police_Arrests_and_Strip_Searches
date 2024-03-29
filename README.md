# Positive Correlation Between Racialization, Gendering and Police Strip Searches in the Toronto Municipal, 2020-2021

## Overview of Repository

This repository contains data, code and a paper that analyze the gender and racial identity of people who have undergone strip searches by the Toronto Police Service in the Toronto Municipal from 2020 to 2021. The dataset used for analysis was retrieved from Open Data Toronto, under the package `Police Race and Identity Based Data - Arrests and Strip Searches`. 

## File Structure

The repo is structured as the following:

-   `input` contains the data sources used in analysis including raw and cleaned data and relevant literature.

-   `outputs/paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper.

-   `scripts` contains the R scripts used to simulate, download and clean data.

## How to Run

1.  Run `scripts/00-simulate_data.R` to simulate envisioned data
2.  Run `scripts/01-download_data.R` to download raw data
3.  Run `scripts/02-data_cleaning.R` to generate cleaned data
4.  Run `outputs/paper/paper.qmd` to generate the PDF of the paper

## LLM Usage Statement

-   No Large Language Models (LLMs) were solicited during the writing of this paper. 
