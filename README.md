# Literacy-Rate-Analysis-Using-GSS-Dataset
Statistical Inference used to analyze disparities in Literacy Rates in the GSS Dataset 

**The Data:**
According to the GSS website, the General Social Survey (GSS) has studied the growing complexity of American society. It is the only full-probability, personal-interview survey designed to monitor changes in both social characteristics and attitudes currently being conducted in the United States.

The GSS contains a standard core of demographic, behavioral, and attitudinal questions, plus topics of special interest. Among the topics covered are civil liberties, crime and violence, intergroup tolerance, morality, national spending priorities, psychological well-being, social mobility, and stress and traumatic events.

As to how the data is collected, the GSS sample is drawn using an area probability design that randomly selects respondents in households across the United States to take part in the survey. The respondents are from a mix of urban, suburban and rural geographic areas. Therefore, random sampling does take place in this survey, meaning the results of the survey can to an extent, be generalized to the adult population of the United States.

There are a few things which might not make it completely accurate. Firstly, the GSS is strictly voluntary, meaning even when selected, participants may choose to not attend the survey. Secondly, up until a few years ago, only English speaking participants were chosen, and now Spanish speaking participants have been added. This raises another concern about other languages, as well.

Random assignment has not been used here to seperate the sampled population into further groups, which means that causality cannot be inferred from the results of this survey, since we cannot be sure that the only difference between different groups is what we are studying.

**Research Questions:**
With such a vast trove of data, it is possible to create many interesting and insightful research questions, each with their own meaningful conclusions.

Here, I will focus on one particular area: education levels. We will analyzing 3 questions based on this area:

*Question 1:* As of 2012 (latest year of the survey), is there a disparity in the education provided to males and females?

In other words, for the 2012 subset,is there any difference between the education levels of males and females? Is there any correlation between education level and gender in 2012?

*Question 2:* In 1972 (first year of the survey), was there a disparity in the education provided to males and females?

In other words, for the 1972 subset,is there any difference between the education levels of males and females? Is there any correlation between education level and gender in 1972?

*Question 3:* Is there a difference in the education levels of 1972 and 2012?

Taking gender out of the equation, is there a difference in education levels of the years 1972 and 2012? Has the situation of education improved or declined in those 50 years?

This is becoming an all-important question in today’s world, with rising calls for equality between men and women. Education is an essential part of gaining knowledge, and an equal footing in education can open up equal opportunities, for men and women. Educational reforms have also been implemented over the years, to provide a higher level of education for all. But has education actually improved, overall?

*Conclusion:*

It can be concluded that: 

(1) There is an insignificant difference in the education levels of males and females in the year 2012, with a 95% confidence interval of (-0.319,0.2384).

(2) There is a significant difference in the education levels of males and females in the year 1972, with a 95% confidence interval of (0.0783,0.7542).

(3) There is a very significant difference in the education levels between the years 1972 and 2012, with a 95% confidence interval of (1.9825,2.4191).

Note: All programming is done using R. The entire code is available in the Rmd file. 
