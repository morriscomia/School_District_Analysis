# Overview of the school district analysis: Explain the purpose of this analysis.
  The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it shows evidence of academic dishonesty. Specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board asked for the data to be removed and analyzed again for a comparison and write up a report to describe how these changes affected the overall analysis.
  
## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

**How is the district summary affected?**

*Original Analysis:*

*Adjusted Analysis:*

![image](https://github.com/morriscomia/School_District_Analysis/blob/0d2e57e48d6b7f17a1df878d43fb6a8fe4352443/Resources/school_data.png)

Although the two are rounded to different decimals and formatted differently, it is clear that the data (district wide) is affected only marginally by the changed the Thomas High School scores. The average scores and percentage passing scores drop slightly. For example, rounding the percent overall passing from the previous school summary to 65.2%, there is only a difference of 0.3% compared to the summary after the changes. Since the scores tend to drop slightly, the ninth-grade scores must have had a positive impact on the data i.e., the percent passing was high.


**How is the school summary affected?**

*Original Analysis:*

*Adjusted Analysis:*
![image](https://github.com/morriscomia/School_District_Analysis/blob/0d2e57e48d6b7f17a1df878d43fb6a8fe4352443/Resources/THS_summary_df.png)

For Thomas High School , the average math and reading scores stays relatively close when changing the scores for ninth graders to NaN. The average math score decreases approximately by .06 (from 83.41 to 83.35) and the average reading score increases by about .05 (from 83.84 to 83.89).

The percent passing math, reading, and overall has around the same marginal changes. The percent passing math decreases by approximately .08% (from 93.27 to 93.19), the percent passing reading decreases by about .29% (from 97.31 to 97.02), and the overall percent passing decreases by around .32% (from 90.95 to 90.63).

While there is an increase in the average reading score, there is a decrease in the percent passing reading. This signifies that there was a large portion of ninth-graders that passed even though their average score was less than the 10th-12th graders average score. This is also true for the reading scores and percent overall passing, there was a higher number of students passing with ninth-grade scores and removing them from consideration brings the overall passing scores down.
**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

**Math and reading scores by grade**

**Scores by school spending**

**Scores by school size**

**Scores by school type**

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
