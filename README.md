# School_District_Analysis

## Overview of the school district analysis
	The purpose of running this analysis on the school district was to be able to present the district's key
metrics and the key metrics for each school in a table format. The analysis allowed the information to be presented
in a way in which could display the top five performing and the bottom five performing schools based on the
condition of overall passing. The script also allowed to understand how each grade was performing at each school,
rather than just observing the performance of the school. Furthermore, the analysis allowed us to see how other
elements in school data such as budet, size, and type may have some correlation with school performance.

## Results
- The district summary before and after making the ninth graders' scores from Thomas High School null does not make
much of an impact because the values that are made null account for only 461 points of data out of the total that is
somewhere close to 40,000.
- The school summary is affected quite significantly when making the ninth graders' scores from Thomas High School,
and this can be seen when comparing the school summary before and after accounting the number of ninth graders'. To
explain, when the school summary was initially created it was performing its calculations for %passing math, %passing
reading, and %passing both were all divide by the student count which still included the the number of 9th graders
that didn't contribute to those percentages. This will lead to an overall lower percentage because we are dividing
by a number that is greater than it should be. Hence, when we account for the new student count which would be only
10-12th graders is lower, and get our new values for %passing math, %passing reading, and %passing both, we see a
significant increase in the percentages. However, if the 10-12th graders reading and math scores were just as bad as
the 9th graders, we would not see an increase in percentage. Another example to show that the 9th graders' scores were
terrible would be to observe the average math and reading scores in the school summaries before and after the student
count has been accounted for. In the before stage, we observe that Thomas High School has scores in reading and math
well around the lower 80's range, and yet, the %passing math, %passing reading, %passing both are lower than 70%
which is odd. However, after the changes have been made, the data table seems to make more sense.
- Replacing the ninth grader's math and reading scores boosts its performance relative to other schools. Before the
changes, we see that the overall passing percentage is around 65%. Fortunately, after replacing the grades of the
ninth graders', we actually see that Thomas High School is actually in the top 5 performing schools based off the
top 5 schools based on performance data table with a 90.6% overall passing rate.
- Replacing the ninth grade scores affect math and reading scores by creating a null value for ninth graders
- Replacing the ninth grade scores affect school spending by increasing the % Overall Passing at a higher value
- Replacing the ninth grade scores affect school size allowing % Overall Passing to be at a higher value at 91
rather than a lower percentage.
- Replacing the ninth grade scores affect scores by school type by contributing to keeping a high % Overall
passing, if the grades were not replaced it would potentially lower the %Overall Passing. However, it would not
change the fact that charter schools significantly outperform district schools in terms of overall passing.

