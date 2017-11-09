
# Introduction
This research study is towards fulfillment of the final project requirement for the DATA 512 class of Fall 2017 at the University of Washington. This ReadMe document contains information on the project plan including details on the research questions, the datasets I plan to use, the provenance information for these datasets, copyright and licensing information for the code, data and documentation, and also some of the Human Centered Design aspects considered in this study.    

<b>NOTE:</b> Some of the links in this document are placeholders and may point to non-existent urls. For such links either the urls will become available or the links will be modified to correct urls before the submission of the final project report on or before 12/10/2017.

# Overview

The goal of this work is to study and explore whether or not there is any dip in the number of people in Seattle who commute to work by bike during the colder days in winter as compared to days on which the weather is warmer. The scope of this study is limited to the commuters west of the lake washington to get to work so I can analyze the Mountain to Sound trail west of I-90 bridge. 

<b>What is known or assumed:</b>

1. On any given day, there are at least some people who commute to work by bike in Seattle. 
2. There are at least some days in winter in Seattle that are very cold. 
3. If people do not commute to work by bike then most of them take alternative form of commute like car, carpool, public transport (bus, train, taxi etc.). 
4. A minor portion of the people who skip the bike commute (in cold weather or otherwise) could also be either walking to work or working remotely. I assume that this number is low. 


<b>Why is this study important:</b>

1. When people do not commute by bike and take an alternative mode, this behavior leads to more congestion (either directly or indirectly, as elaborated below). More congestion can cause longer commute times and may also contribute to air pollution.   

    a. The congestion impact is direct when this alternative mode of commute is car or taxi because it directly adds a motorized vehicle on the road. The side assumption here is that the taxi taken by a person is otherwise free and not on road during that time. Also, the contribution to pollution is only when this motorized vehicle produces exhaust (eg. non-electric vehicles). 
    
    b. The impact is indirect when the alternative mode of commute is a carpool or a bus or a train, because even in this scenario there is an increase in the number of commuting people on the road by means other than bike and are still consuming the transportation resources. In this scenario it can be argued that there is no added impact when these people only increase the occupancy ratio of the existing fleet. And it is only when the fleets exceed their capacity requiring more fleet to be added that the real impact will begin to be noticed. 
    
2. As we know, bike riding is a very good form of exercise. We could conclude that when people bike to work they are getting better exercise. If these people do not bike to work and assuming some of them do not compensate this exercise with any other form, they are losing out on the health benefit.

    In both the scenarios mentioned above, we can see there is impact to humans and is an example of one of the values of a Human Centered Study Design.  
    
<b>Other considerations:</b>

1. Since the dataset(s) span multiple years, there would be a need to control for the population growth and increased number of bikers while doing the analysis. 
2. The routes taken by the different bikers as well as the start and destination are not being taken into account. I am only considering the bike commuter volume at any given point as a raw number. 

   
# Datasets

For this work, I intend to take advantage of the following publicly available datasets: 

1. The bike traffic at different points in the city (including Daily, Weekly, and Annual patterns) in the Mountain to Sound trail are available at the City of Seattle Open Data portal's page on [MTS-Trail-west-of-I-90-Bridge](https://data.seattle.gov/Transportation/MTS-Trail-west-of-I-90-Bridge/u38e-ybnc). 

2. The road and air temperature data for different locations throughout the city is available at the City of Seattle Open Data Portal's page on: [Road Weather Information Stations](https://data.seattle.gov/Transportation/Road-Weather-Information-Stations/egc4-d24i)



# Copyright and Licensing

The code, text of the repository will be governed by the MIT License to be included in the [LICENSE file](https://github.com/sumanbhagavathula/data-512-finalproject/blob/master/LICENSE)

The wikipedia articles data is available under the [Creative Commons BY](https://creativecommons.org/licenses/by/2.0/)
The ORES scores data is available under the [Creative Commons 0](https://creativecommons.org/publicdomain/zero/1.0/)
The PRB data is copyrighted and is not available and hence not included with this repo. You may choose to download this data directly from source that is mentioned in the Data Provenance section below.

More information on the Open Data Initiative can be viewed at the City of Seattle's Open Data Initiative [Information page](http://www.seattle.gov/tech/initiatives/open-data), the [Warranty information page](https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/), the [policy page](http://www.seattle.gov/Documents/Departments/SeattleGovPortals/CityServices/OpenDataPolicyV1.pdf) and the [privacy page](http://www.seattle.gov/tech/initiatives/privacy)

<b>[Required Disclaimer by City of Seattle (see "Source Data" section:](https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/)</b>

The data made available here has been modified for use from its original source, which is the City of Seattle. Neither the City of Seattle nor the Office of the Chief Technology Officer (OCTO) makes any claims as to the completeness, timeliness, accuracy or content of any data contained in this application; makes any representation of any kind, including, but not limited to, warranty of the accuracy or fitness for a particular use; nor are any such warranties to be implied or inferred with respect to the information or data furnished herein. The data is subject to change as modifications and updates are complete. It is understood that the information contained in the web feed is being used at one's own risk.



## Description of the process
The end to end process of this analysis work will broken down into four steps:

1. Data Acquisition
2. Data Processing
3. Analysis and Visualization
4. Conclusion

For final project, I will be publishing steps to this README file that will help any readers who want to either reproduce or replicate the results of this study. 

## File structure
The source code, data (raw and processed) will be placed in the following structure:

### Source
The source code will be located in the [github repo source code file](https://github.com/sumanbhagavathula/data-512-finalproject/blob/master/src/hcds-finalproject.ipynb) and containing documentation and code for all the three steps mentioned above.

### Data
1. [Raw Data](https://github.com/sumanbhagavathula/data-512-finalproject/tree/master/src/data/raw) will contain any raw data files. 

2. [Processed Data](https://github.com/sumanbhagavathula/data-512-finalproject/tree/master/src/data/processed) will be the location for the processed data

3. [Analysis and Visualization Data](https://github.com/sumanbhagavathula/data-512-finalproject/tree/master/src/data/processed) will contain any data transformations that were generated in the analysis phase and copies of any visualizations that may be created as part of this work.


# Dependencies

The City of Seattle mentions on their [Data Policy page ("see Right to Discontinue Feeds") section](https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/) that they do reserve the right to discontinue or provide any or all of the data feeds at any time. 


# Acknowledgements

I would like to thank the instructor and TA for the class (Prof. Jonathan Morgan and Oliver Keyes respectively) who have gathered information on the datasets and allowed us to use them for my work. Also, many thanks to the City of Seattle's Leadership and the Open Data Initiative team for providing the valueable datasets that were of use in this research study, without which this research work may not have been possible. 
