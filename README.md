# kickstarter-analysis
performing analysis on Kickstarter data to discover trends

### Challenge

## Outcomes Based on Goals

* For play campaigns less than $5000 there is a strong likelihood of receiving the minimum funding (~75%).
* For Goals between $5000 and $25000 campaign success is nearly a coin-flip with 5% success erosion with each larger goal tranche. 
* Once the goal becomes larger than $25000 the odds are long that the campaign will succeed though the data set becomes less statistically significant (fewer than 30 samples per goal range). There is actually a slight tick-up with campaigns greater than $35000 but with so few samples it is unreasonable have confidence there is a legitimate trend reversal. 

Limitations
* This analysis excludes the 19 currently running (Live) campaigns though it's doubtful that including that data would skew the results that dramatically. They are roughly split into two ranges 1) less than $10k and 2) greater than $10k. As current, less than 10% of the smaller group has received minimum funding and 25% of the larger ground has received minimum funding. 

## Outcomes based on Launch Date
* As it stands, it looks like the time to launch is May and June as there is a big jump between April to May. While success drops in the two months that follow, June and July are still higher than any other month. 
* While the count for unsuccessful campaigns is lower than successful, the unsuccessful campaigns exhibit consistent trends with lower amplification. I.e. There is an uptick of unsuccessful campaigns starting in April, peaking in May and slowly decreasing to September. 
* When looking at year-over-year visualizations (included separately in the worksheet), theater campaigns accelerated dramatically in 2014, peaked in 2015 and dropped 25% in 2016. As only January and February 2017 data is provided it's impossible to say if campaigns overall, successful and failed will continue to drop. A quarter-over-quarter segmentation supports the possibility that popularity for Kickstarter theater campaigns has peaked in popularity (2015-Q2) and is seeing 15-30% quarterly market erosion. 

Limitations
* This chart is not broken out by year. One hypothesis that could be tested is "Did Kickstarter as a company start mid-year so we may not have a full 'fiscal year' to compare to." While not broken out in the chart, the underlying data appears to confirm this as June 2014 is when data collection begins and runs through February 2017. As a result, its reasonable to expect March and April to flatten out the dip shown in those months. 

## Additional considerations:
* What may be interesting to view is a comparision (and possible correlation) between the percent of goal raised and the duration of the campaign. I expect this would be a scatter-plot to determine if any particular grouping emerges. 
* While the data does not provide this level of detail, it might be interesting to see a histogram of the average donation for both successful and failed campaigns. Are the successful campaigns receiving lots of small donations to meet the objective or is there a high dollar contribution that is getting things moving? 
* Also does a virtuous cycle emerge early after launch where a campaign builds "buzz" and momentum takes over? Do successful campaigns receive a disproportionate number of contributions immediately and thin out quickly? If this were true, it could be easy to see if some different marketing could be implemented to drive up contributions. 
* While the information is rich, it does not include information such as views/clicks and other marketing efforts. Much like realtors use 'coded' language, can blurbs be optimized to drive more views and presumably contributions? 
