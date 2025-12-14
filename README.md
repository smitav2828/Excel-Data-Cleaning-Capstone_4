# Excel-Data-Cleaning-Capstone_4

# Day 4 Capstone – Data Cleaning for FastFit Gym

## Scenario

I worked as the Data Processor for FastFit Gym. The marketing team gave me a messy signup list from a recent event, and I had to clean it up for emailing.

## Problems in the Dataset

* Names were flipped and lowercase (e.g., "doe, john")
* Phone numbers had different formats like (555)-123-4567 and 555.123.4567
* Age column had invalid values like 999 or text such as "twenty"
* Membership had inconsistent casing and extra spaces like "Gold", "gold ", "GOLD"
* Duplicate signups existed based on Email or Phone

## Steps Taken

1. Removed duplicates using Email and Phone as criteria
2. Fixed Name format using Flash Fill or text formulas to get proper "First Last"
3. Cleaned Phone numbers by removing parentheses, dashes, and dots using Find & Replace
4. Applied Data Validation to highlight invalid Ages using the Circle Invalid Data tool
5. Used TRIM and PROPER functions on Membership column to fix spaces and casing
6. Protected the sheet to prevent accidental changes after cleaning

## Excel Skills Used

* Removing duplicates
* Flash Fill and text functions
* Find & Replace
* Data Validation and error checking
* TRIM and PROPER for text cleanup
* Sheet protection

## Summary

This task helped improve data quality and prepared a clean contact list for marketing emails. The sheet is now easy to use and reliable.


