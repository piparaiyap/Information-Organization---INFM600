# Information-Organization---INFM600
The repository is a part of assignment submission for INFM600

Focal Data Set: Liquor Licenses in Howard County as of October 2015
Citation: Howard County Council - Liquor Board (2015). Liquor Licenses. [Data file]. Howard County - Maryland. Retrieved from: https://opendata.howardcountymd.gov/Licenses-and-Permits/Liquor-Licenses/tk3t-mn7e. Date Accessed: 10/27/2015.
Description: The data set provides a list of liquor licenses issued to traders to sell alcoholic beverages in Howard County. It includes name and location of corporations permitted to sell liquor along with the type of license issued and whether the license is active or inactive. The focus of the data set would be the location of liquor store which will be used for further analysis.

Additional Data Set -1: Howard County Police Department Call for Service: 2014
Citation: Howard County – Police Department (2014). Howard County Police Department Call For Service: 2014.  [Data file]. Howard County - Maryland. Retrieved from: https://opendata.howardcountymd.gov/Public-Safety/Howard-County-Police-Department-Call-For-Service-2/qccx-65fg/about. Date Accessed: 10/27/2015.
Source: https://opendata.howardcountymd.gov/Public-Safety/Howard-County-Police-Department-Call-For-Service-2/qccx-65fg
Description: The data set provides calls for service logged in Computer Aided Dispatch systems used by Howard County Police Department. It includes the type of event reported (assault, theft, traffic hazard etc.), date, time and location where the event took place. 

Additional Data Set -2: Schools - High
Citation: Howard County GIS (2014). Schools – High. Howard County – Maryland [Map]. Retrieved from: https://data.howardcountymd.gov/InteractiveMapV3.html?Workspace=IndividualLayer&Layer=general:Schools_High&LayerName=Schools%20-%20High. Date Accessed: 10/27/15.
Description: The data set provides geometric location of High Schools in Howard County on a map. In CSV format it includes the name of school, address, zip code and geometric coordinates.


Analysis of Focal Dataset and Additional Dataset 1:

For analysis, we merge the two datasets together on column 'Address' in Dataset 1 (or 'Location' in Dataset 2). 

The process documentation for merger can be found in 'Workflow Documentation_Merger.pdf'

Merged dataset created: Merged - Liquor Store and Criminal Incidents.xlsx
Citation: Piparaiya, P. (2015). Merged - Liquor Store and Criminal Incidents. [Data file]. INFM600-Information-Organization. Available: https://github.com/prakritipiparaiya/INFM600-Information-Organization

Research Question:  Does presence of liquor stores influence criminal activity in neighborhood areas?
Presence of liquor stores (bars, restaurants, convenience stores) in residential areas can result in increased criminal activity, vandalism and in-orderly conduct. This can endanger the safety of neighborhood residents and adversely affect the quality of life of residents. The results of analysis can be used by Howard County in the following ways:
1. Liquor licenses are not issued for residential areas. 
2.In case license is issued, the type of license being issued should be restricted to Class A – Off sale packaged goods, no on-premises consumption.
3. Patrolling can be increased in areas where liquor stores are present.
4. Presence of bars and restuarants can also affect traffic and parking issues. 

Reporting analysis results: As the focus of datasets is the location of liquor stores, the results of analysis can be best reported via a map. The location of liquor stores along with criminal incidents reported can be plotted on a Howard county map. The density of criminal activities can also be conveniently depicted on the map and used for further analysis.  

Analysis of Focal Dataset and Additional Dataset 2:

Merging focal dataset and dataset for High schools locations in Howard County allows us to answer the following research question:

Are liquor stores strategically located in areas near schools to attract the young population?
The legal age for alchohol consumption in Maryland is 21 years. However high school may students indulge in underage drinking due
to peer pressure or in their quest to experiment. Liquor stores can cater to this audience and open stores in areas which are easily accessible by students. The analysis of the two data sets can help answer this question whether there is presence of liquor stores near schools. HoCo can use this analysis to:
1. Restrict functioning of liquor stores in areas close to schools
2. Identify non compliant liquor stores (for serving underage drinkers)

License: Merged - Liquor Store and Criminal Incidents by INFM600-Information Organization is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

The data contained in Focal Dataset -Liquor_Licenses.xlsx, Additional Dataset – Police CAD Event.xlsx has been obtained from 'Open Howard - HowardCounty Data Portal' and are open for Public use. 

The data contained in Additional Dataset - Schools_High.xlsx has been obtained from 'Open Howard - HowardCounty Data Portal, GIS Division' and uses Creative Commons Attribution 4.0 International Public License.
