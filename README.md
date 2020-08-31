# Challenge Assumptions
## Assumption 1:
Call to the function performs full data load only

## Assumption 2:
Data files contain full data set and not incremental data pulls

## Assumption 3:
Try except blocks throw errors in case data files are not found, there are issues connecting to the database and loading data.

## Assumption 4:
Regex patterns used are based on analysis of data. Any changes in the data files need to be analyzed and code changed appropriately to accomodate for new regex patterns

## Assumption 5:
Column names do not change in the data
