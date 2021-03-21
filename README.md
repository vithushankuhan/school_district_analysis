# School District Analysis

## Overview of Project

The purpose of this project is to analyze school district data and uncover trends in school performance using Pyhton and Pandas. More specifically, the school board has found evidence of academic dishonesty for math and reading grades at Thomas High School. In order to uphold their state-testing standards, this project was conducted to replace the grades from Thomas High School. The analysis conducted wil help determine how the suspected academic dishonety affects school performance.

## Results

Removing 9th grade student scores from Thomas High School affected the rest of the school district in the following ways:

Before Cleanup

<img width="946" alt="Screen Shot 2021-03-21 at 5 37 49 PM" src="https://user-images.githubusercontent.com/76541288/111921679-3aa62480-8a6c-11eb-8dbb-c16f4945237c.png">

After Cleanup

<img width="942" alt="Screen Shot 2021-03-21 at 5 38 38 PM" src="https://user-images.githubusercontent.com/76541288/111921687-48f44080-8a6c-11eb-9cba-1b4b2803dbf3.png">

- Total Students: Remained unchanged
- Total Budget: Remained unchanged
- % Overall Passing: Took a very slight decline by 0.1%
- % Passing Math: Took a very slight decline by 0.2%
- % Passing Reading: Took a very slight decline by 0.3%
- Average Math Score: Took a very slight decline by 0.1%
- Average Reading Score: Remained unchanged

What it clear from this information is that removing the math and reading grades from 9th graders at Thomas High School had an insignificant impact on the overall performance of the school district. 

The first image can be found in PyCitySchools.ipynb.
The second image can be found in PyCitySchool_Challenge.ipynb

## Summary

While changes at the district level were insignificant, the impact of removing 9th grade scores did leave a mark at the school level. Four major changes were observed after analyzing the data with removed 9th grade results.

1. Overall Passing dropped from 90.9% to 65.1%.
2. It is clear the the performance of Thomas High School relative to other schools drops significantly as the overall passing percentage drops by a lot. Prior to removing the 9th grade scores, Thomas High School was a top 3 performing school. However, after this this incident it clearly at the bottom of the list.
3. Third, the medium bin will also see a signifit decrease in the passing percentage since Thomas High School was in that bin. 
4. Finally, a significant drop in math and reading scores can be observed. Passing math dropped from 93.2% to 66.9%. Passing reading dropped from 97.3% to 69.6%

In summary, the analysis conducted on the school district provides interesting insight into the performance of each school within the district. Events like the one in the present study present a unique opportuniy to understand how changes in school performances impact individual and district performance. With that being said, the results from this project presents the school board with valuable information into how situtations like academic dishonesty should be handled in the future. 
