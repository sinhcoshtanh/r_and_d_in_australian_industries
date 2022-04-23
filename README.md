# r_and_d_in_australian-industries


<p align="center">
  <img src="https://media.giphy.com/media/LPZcp219tMH5OPeYEK/giphy.gif" />
</p>

## Introduction:
The transition from pre-COVID to the economic downfall that was due to the pandemic lead businesses in multiple industries to reconsider their business model and merchandise due to the restriction on the purchasing power from face-to-face transactions. In this analysis we shall extract data mined between 2017 - 2020 by the [Australian Bureau of Statistics (ABS)](https://en.wikipedia.org/wiki/Australian_Bureau_of_Statistics) to discuss the money commited for [Business expenditure for R&D (BERD)](https://en.wikipedia.org/wiki/Research_and_development)  in each industry in Australia to reveal any potential trends regarding the industry's growth and future foresights.

## Data set Fields:
### Key notices
- Originally the provided data set categorised the industries under 'Industry' and 'Subindustry', these have been changed to 'Division' and 'Subdivision' as defined by the ABS by [1292.0 - Australian and New Zealand Standard Industrial Classification (ANZSIC), 2006 (Revision 1.0)  ](https://www.abs.gov.au/ausstats/abs@.nsf/0/20C5B5A4F46DF95BCA25711F00146D75?opendocument).

- While 'Industry', 'Sub-industry', and 'Total expenditure on R&D' are personally defined according to the value of the data provided. The remaining Fields are defined by the ABS by [1297.0 - Australian Standard Research Classification (ASRC), 1998](https://www.abs.gov.au/ausstats/abs@.nsf/66f306f503e529a5ca25697e0017661f/22E4C184CA111129CA25697E0018FD78?opendocument).

|New name|Description|
|---|---|
|Division|Branch of economy dedicated to manufactor a new certain good, as defined by the [ABS](https://www.abs.gov.au/statistics/industry)|
|Subdivision|The more specific class of the industry|
|Pure basic research|Experimental and theoretical work undertaken to acquire new knowledge without looking for long term benefits other than the advancement of knowledge.|
|Strategic basic research|Experimental and theoretical work undertaken to acquire new knowledge directed into specified broad areas in the expectation of useful discoveries. It provides the broad base of knowledge necessary for the solution of recognised practical problems.|
|Applied research|Original work undertaken primarily to acquire new knowledge with a specific application in view. It is undertaken either to determine possible uses for the findings of basic research or to determine new ways of achieving some specific and predetermined objectives.|
|Experimental development|Systematic work, using existing knowledge gained from research or practical experience, that is directed to producing new materials, products or devices, to installing new processes, systems and services, or to improving substantially those already produced or installed.|
|Total expenditure on R&D|The estimated total amount of money (AUD) spent on including the hidden amounts due to data privacy protection.|

## Objectives:
- Top Industries' commitment to R&D.
- Top States and Terrortories with the largest commitment to R&D.
- Types of Research with the largest commitment to R&D.

## Results:
<details><summary>Top Industries' commitment to R&D</summary>
<p>

It was able to extract that the top 3 industries alone contribute to approximately 75% of the BERD contribution. These industries in descending order are
1. [Professional, Scientific, and Technical Services](https://business.gov.au/planning/industry-information/professional-scientific-and-technical-services-industry) having had the greatest contribution to the BERD ($6.101 billion AUD/34%).
2. [Manufacturing](https://business.gov.au/planning/industry-information/manufacturing-industry) ($4.763 billion AUD/26%).
3. [Financial and Insurance Services](https://business.gov.au/planning/industry-information/financial-and-insurance-services-industry) ($2.714 billion AUD/15%).
  
From Figure 1 it can be concluded that there was on average a 6.7% increase on the funding for Research and Development. Even after adjusted for inflation at a 0.89% according to the [Reserve Bank of Australia](https://www.rba.gov.au/inflation/measures-cpi.html).
  
It should also be pointed out that there was an overall redistribution of the funding for the BERD, as industries such as Retail Trade, Construction, and Information Media, Telecommunications, which could have been reallocated to Professional, Scientific, and Technical Services from large telecommunications and technology companies merging (ie. Telstra, Afterpay and Block).
  
 This can be accredited to the transition away from face-to-face/in person business operations to virtual and online business operations. This includes the (essentially) mandatory and fundamental dependency on the use of over the internet communications to keep in contact with families. It should be taken into investigation regarding the use of internet from each different age group over the pandemic. This transition also includes the use of online shopping for everyone's grocery shopping and personal goods, as a result from [news reports](https://auspost.com.au/content/dam/auspost_corp/media/documents/2020-australia-post-annual-report.pdf) CONTINUE

![Top 10 Industry's Commitment to Research and Development Graph](https://github.com/sinhcoshtanh/r_and_d_in_australian_industries/blob/4604ffce2017510612342ce0ea47a7a76f6ca1d3/files/graphs_and_tables/top_10_industry_graph.png)
Figure 1: Top 10 Industry's Commitment to Research and Development Graph
  
![Top 10 Industry's Commitment to Research and Development Table](https://github.com/sinhcoshtanh/r_and_d_in_australian_industries/blob/4604ffce2017510612342ce0ea47a7a76f6ca1d3/files/graphs_and_tables/top_10_industry_table.png)
Figure 2: Top 10 Industry's Commitment to Research and Development Table
  
</p>
</details>

<details><summary>Top States and Terrortories with the largest commitment to R&D</summary>
<p>

</p>
</details>

## Files:

The data set files can be downloaded directly from the original source from the Australian Bureau of Statistics or in the GitHub repo.
|Data set|Year|Web download|GitHub download|
|---|:---:|:---:|:---:|
|Business expeniture on R&D, by ANZIC06 industry subdivision, by type of activity|2017-18|[Web Link](https://www.abs.gov.au/statistics/industry/technology-and-innovation/research-and-experimental-development-businesses-australia/2017-18/81040do006_201718.xls)|[GitHub Link](https://github.com/sinhcoshtanh/R-and-D-in-Australian-Industries/blob/5a6d2ae8ec7023b61b99c9a246384c33289c995c/files/datasets/original-datasets/2017-18/type-of-activity-2017-18.xls)|
|Business expeniture on R&D, by ANZIC06 industry subdivision, by location of expenditure|2017-18|[Web Link](https://www.abs.gov.au/statistics/industry/technology-and-innovation/research-and-experimental-development-businesses-australia/2017-18/81040do005_201718.xls)|[GitHub Link](https://github.com/sinhcoshtanh/R-and-D-in-Australian-Industries/blob/5a6d2ae8ec7023b61b99c9a246384c33289c995c/files/datasets/original-datasets/2017-18/location-of-expenditure-2017-18.xls)|
|Business expeniture on R&D, by ANZIC06 industry subdivision, by type of activity|2019-20|[Web Link](https://www.abs.gov.au/statistics/industry/technology-and-innovation/research-and-experimental-development-businesses-australia/2019-20/81040DO006_201920.xls)|[GitHub Link](https://github.com/sinhcoshtanh/R-and-D-in-Australian-Industries/blob/5a6d2ae8ec7023b61b99c9a246384c33289c995c/files/datasets/original-datasets/2019-20/type-of-activity-2019-20.xls)|
|Business expeniture on R&D, by ANZIC06 industry subdivision, by location of expenditure|2019-20|[Web Link](https://www.abs.gov.au/statistics/industry/technology-and-innovation/research-and-experimental-development-businesses-australia/2019-20/81040DO005_201920.xls)|[GitHub Link](https://github.com/sinhcoshtanh/R-and-D-in-Australian-Industries/blob/5a6d2ae8ec7023b61b99c9a246384c33289c995c/files/datasets/original-datasets/2019-20/location-of-expenditure-2019-20.xls)|

## Discussion:

### Improvements
- Import the analysis from xlsx to csv then run Python scripts under the Jupyter Notebook. This can be found [here]()

### Limitations
- As I assume that there as an overhaul of the interface of the ABS's web interface I was not able to extract the data sets for 2011-12, 2013-14, and 2015-16. As a result it was required to create data from the original website's overall summary of these years, not allowing for more deep data mining and analysis for these years.
- These data sets were not able to be provided in [.csv](https://en.wikipedia.org/wiki/Comma-separated_values) format, rather exclusively as a restricted .xlsx file. As a result, data was mined and analysed by simple data extraction from the values of the table onto another .xlsx file.
