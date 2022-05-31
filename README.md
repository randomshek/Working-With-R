# Working-With-R

**transactions.csv**: contains synthetic data relating to a hypothetical research analysis on a set of online banking transactions. The dataset has 600 instances (rows) and 8 attributes (columns).

The purpose of the study for which the data has been gathered is to evaluate the effectiveness of 
the new algorithm, whose accuracies are given by variable model2, relative to the performance of 
the benchmark algorithm, whose accuracies are given by variable model1.

**SECTION 1: VISUALISATIONS AND SUMMARY STATISTICS**

Generated the following charts/diagrams and, hence, addressed the requested comments.
> 1.1 Create a histogram plot showing the distribution of the values for model2. Also, calculate the mean and median values for model2. Comment on whether model2 shows a normal distribution?

> 1.2 Create a histogram plot showing the distribution of the values for value. Also, calculate the mean and median values for value. Comment on whether value shows a normal distribution?

> 1.3 Create a boxplot of the value variable split by the recipient category. Calculate the mean and standard deviation of value for each type of recipient. Comment critically on the dependence of value on the recipient type.

> 1.4 Create a scatterplot of time against value with the points colour coded according to the 
device. Calculate the correlation of value and time. Comment critically on the dependence of time on value.

> 1.5 Create two stacked barplots, one with the frequencies of device against status (and the 
other vice versa). Comment critically on the dependence of device and status.

**SECTION 2: TABLES & MEASURES**

Generated the following tables/descriptive statistics and, hence, addressed the requested comments.

> 2.1 A one-way table of frequencies (counts), relative proportion and cumulative frequencies for recipient. What are the most common, and what are the rarest recipient types?

> 2.2 A two-way table of recipient (in rows) and status (in columns) normalised to show the 
fraction of status for each recipient type. Comment critically on any interesting observations.

> 2.3 A table showing the mean of model2 broken down by status. A table showing the mean of model2 broken down by device. Comment critically on any interesting observations.

**SECTION 3: SIGNIFICANCE TESTS**

Performed the following statistical analyses.

> 3.1 Determine a 99% confidence interval for the mean value of model1 and model 2. For each, 
state the mean value and the confidence interval.

> 3.2 Perform and interpret a paired two sample t-test to test for evidence of a difference in the performance of model2 compared to the performance of model1 across all the data. Perform a second t-test to assess the hypothesis that model2 outperforms model1 by a difference of 2. For both tests use a significance level of 0.05.

> 3.3 Use a non-parametric test to check for evidence of reduced performance of model2 on New
recipients compared to Existing recipients. Perform the same type of test but to check for a difference in performance of model2 for PC device compared to tablet device. Use a significance level of 0.01 for both tests.
 
> 3.4 Perform a one-way analysis of variance with Tukey’s multiple comparisons to compare the 
model2 performance for the different types of recipient. Use a significance level of 0.05 for 
the ANOVA test, and a 95% confidence level for Tukey’s comparisons. Check the assumptions required for ANOVA and comment in the validity of the test.

**SECTION 4: EXPERIMENT DESIGN, SAMPLE SIZES AND RANDOM SAMPLING**

> 4.1 Calculate the standard deviation of model2

> 4.2 Calculate the minimum sample size required to perform a 2-sample t-test of statistical 
power 0.9 for establishing a difference of 2 in performance if a two-sided test is to be 
performed with significance level 0.05 and the estimated standard deviation assumed to be 
the value calculated in task 4.1 above. How large a sample would be needed to increase the power of the test to 0.99 with 
significance level 0.01?

> 4.3 Let n be the first sample size calculated from 4.2 above. Create a data frame using a random sample of size n from transactions (with no duplicates). Compare the distribution of the recipient values in the sample to the complete dataset.

> 4.4 Suppose that you had intended to create a stratified random sample that had occurrences 
of recipient in the (approximately) same proportion as the transactions dataset. Create a 
dataframe (with no duplicates) of size n with these properties and ensure that the sample is 
reproducible.
