# data-sourcing-challenge
Module 6 Homework_Data sourcing from NOAA

**Data download via API & manipulation**

## Table of Contents
* [Introduction](#introduction)
* [Installation Requirements](#requirements)
* [Usage](#usage)
* [License](#license)
* [Acknowledgement / Contributing](#acknowledgementcontributing)

## Introduction
This project is the sixth coding module challenge that we had to complete as part of the Denver University AI Bootcamp coursework. 

The initial code provided for the challenge had us obtain a API Key from NASA to access / download data from the site by creating specific URLs for data sets of interest. Two dataframes were created from the downloaded data and then manipulated, as one specific column included a lists. New rows were created for each data point within the list using 'for loops' and the 'explode' function. The two dataframes were then merged on a common date_time stamps and IDs to create a single dataframe. Lastly, we calculated some time differences between the two timezone columns and the file was exported as a .csv.


## Installation Requirements
*Requirements*: You must run Python 3.12.7 to execute the code as the code uses match case sytax that is older versions of python will not recognize.

## Usage
Anyone that would like to understand how to get data from a site that needs and API key. Additionally, to understand how to create fuller dataset by exploding a list of multiple events associated with a single data point (eg. a day). 

## License
I've included the MIT License to encourage collaboration and use by the community.

## Acknowledgement / Contributing
Thank to the guidance of the Denver University AI Bootcamp Teachers Assistant's and their hints via comments that helped me complete this assignment. Without this I would've been completely lost. 

While a section of this code was written by the Denver University AI Bootcamp Teachers Assistant, it has been modified / completed by me. 

