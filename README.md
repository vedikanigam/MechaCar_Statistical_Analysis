# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Summary MPG LM](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/summary_lm_mpg.png)

From the summary output, we can see the p-value of vehicle length(2.60e-12) and ground clearance(5.21e-08) is below 0.05. Therefore, ground clearance and vehicle length have a statistically significant impact on MPG.

The p-value of this multiple linear regressionmodel is 5.35e-11 which is smaller than our assumed significance level of 0.05%. Therefore we can state that there is sufficient evidence to reject our null hypothesis which means that the slope of the linear model is not zero. 
 
This linear model predicts the mpg of MechaCar prototypes effectively as the r-square value is 0.71 which means that approximately 71% of the variability of MPG is explained by the independant variables.

## Summary Statistics on Suspension Coils

![Total Summary](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png)

The total summary statistics of the PSI column shows that the variance of the suspension coils of vehicles from all manufacturing lots is 62.3 which does not exceed 100 pounds per square inch as per the design specification. 

![Lot Summary](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png)

However, when the data is categorized by manufacturing lots, the variance of the suspension coils for vehicles from lot 1(0.98) and lot2 (7.47) is below 100 but from lot 3 is above 100(170.29).  

## T-Tests on Suspension Coils

### T-Test on all Manufacturing Lots

![t-Test All Manufacturing](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/AllManufacturingLot_TTest.png)

The p-value from T-test on all manufacturing lots is 0.06. Assuming significance level of 0.05 percent, our p-value is above our significance level. Hence we do not have significance evidence to reject the null hypothesis which assumes that the mean is equal to the population mean of 1500 pounds per square inch. 

### T-Test on each individual Manufacturing Lot

![t-Test Lot1](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/Manufacturing_Lot1_TTest.png)

The p-value in Lot 1 is 1 therefore we cannot reject the null hypothesis. 

![t-Test Lot2](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/Manufacturing_Lot2_TTest.png)
The p-value in Lot 2 is 0.6 therefore we cannot reject the null hypothesis.

![t-Test Lot3](https://github.com/vedikanigam/MechaCar_Statistical_Analysis/blob/main/Images/Manufacturing_Lot3_TTest.png)
The p-value in Lot 2 is 0.04 hence we can reject the null hypothesis. Therefore the mean is not equal to the population mean of 1500 pounds per square inch for this lot.

## Study Design: MechaCar vs Competition

This statistical study will test highway fuel efficiency of MechaCar against the competion. First, we will measure highway fuel efficiency and horsepower for a large sample of vehicles from MechaCar and from the competition.

The null hypothesis will be the fuel efficiency of MechaCar is less than or equal to the competition.
The alternative hypothesis will be the fuel efficiency of MechaCar is greater than the competiton.

We will use two-sample unpaired t-Test to see whether the means of two samples are statistically different. 

We will use highway fuel efficiency and horsepower data for a large sample from MechaCar and the competition. 

