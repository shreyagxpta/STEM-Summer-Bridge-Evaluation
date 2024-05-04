# STEM-Summer-Bridge-Evaluation
This project is by Shreya Gupta for UC Berkeley's Data Science Honors Program (H195A & H195B 2023-2024). 
Advisor: Professor Narges Norouzi, UC Berkeley.

This project aims to create a pipeline which can be used to evaluate the impact of STEM-based summer bridge program via a multitude of non-academic indicators (e.g. feeling of belongingness, attitude to seeking help, etc.) and academic indicators (like final grades). This study is being set up with analysis of only one summer bridge program (the Baskin School of Engingeering Summer Bridge Program for underrepresented students), so all data cleaning and formatting is done with respect to this particular dataset. 

To replicate and use the provided code exactly, ensure all data is in the correct format and in the correct path. 

All Data must be imported from an appropriate directory. To use the exact code provided, including imports, ensure that all data is located on Google Drive using the following path: '/content/drive/My Drive/BEES Research Data/Data for Studies/_.xlsx'
Instead of _, one must have data in one of these 3 formats: 'YEAR Post Survey.xlsx', 'YEAR Pre Survey.xlsx', 'YEAR Academic Performance.xlsx'. For the purposes of the current study, YEAR = 2020, 2021, 2022, or/and 2023.

For Pre-Surveys: Reference "Pre Survey Format.xlsx". Note that all cells must be in the same string format as the sample data provided. All scores are between 1 and 6, except for HelpSeeking and Concealment (which are in between 1 and 4). 

For Post-Surveys: Reference "Post Survey Format.xlsx". Note that all cells must be in the same string format as the sample data provided in Pre Survey Format.xlsx. All scores are between 1 and 6, except for HelpSeeking and Concealment (which are in between 1 and 4). However, there are 11 additional qualitative columns that accept unique student responses. Namely, these are columns: "Q24", "Q26", "Q28", "Q30", "Q34", "Q38", "Q42", "Q44", "Q46", "Q48", "Q50"

For Academic Performance Data: Reference "Academic Performance Format.xlsx". Note that all cells must be in the same string format as the sample data provided in the reference document. Note that the status column accepts multiple formats. The main components of a string must be "Declared", "Proposed", "good standing", "ok standing", "weak standing" as these are used in majority of the analyses included in the thesis.

For any questions, please contact shreya.g@berkeley.edu.
