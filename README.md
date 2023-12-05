# MIST4610_Project2

## Team Name
39217 Group 4

## Team Members
Ethan Berry [@ethanberry](https://github.com/ethanberry)   
Esha Bhat [@ohesha](https://github.com/ohesha)   
Anna Kerber [@ackerber](https://github.com/ackerber)  
Pranay Patel [@Pranay416](https://github.com/Pranay416)  
Rafe Rynne [@IsThatCanon](https://github.com/IsThatCanon)   
Jameson Shi [@jameson-shi](https://github.com/jameson-shi)   

## Description of Data Set
Our dataset comprises a comprehensive record of shooting incidents that have transpired in New York City since 2006 up until the conclusion of the preceding calendar year. This meticulously curated data undergoes a manual extraction process every quarter, rigorously reviewed by the Office of Management Analysis and Planning before its publication on the NYPD website.

Each entry within this dataset encapsulates a distinct shooting incident transpiring in NYC, offering detailed insights into the event, its precise location, and occurrence time. Moreover, it furnishes comprehensive information regarding the demographics of both suspects and victims involved in these incidents. This dataset contains 27,312 rows and 21 columns.

The dataset features multiple dimensions mirroring diverse aspects of the incidents, such as:

Incident ID: Number (Unique identifier for each shooting incident)  
Occurrence Date: Date (Date of the shooting incident)  
Occurrence Time: Time (Time of the shooting incident)  
Borough: String (Location within NYC where the incident occurred)  
Location Description: String (Description of the incident location)  
Precinct: Number (Police precinct associated with the incident)  
Jurisdiction Code: Number (Code specifying jurisdiction details)  
Classification Description: String (Description of incident classification)  
Additional Location Details: String (Further details about the incident location)  
Statistical Murder Flag: Boolean (Indicator if the incident resulted in a murder)  
Suspect Age Group: String (Age group of the suspect involved)  
Suspect Sex: String (Gender of the suspect involved)  
Suspect Race: String (Race of the suspect involved)  
Victim Age Group: String (Age group of the victim involved)  
Victim Sex: String (Gender of the victim involved)  
Victim Race: String (Race of the victim involved)  
X Coordinate: Number (Spatial coordinate X)  
Y Coordinate: Number (Spatial coordinate Y)  
Latitude: Number (Latitude of incident location)  
Longitude: Number (Longitude of incident location)  
Lon_Lat: String (Combined longitude and latitude information)  

This dataset serves as a valuable resource for the public, facilitating an exploration of the nature and patterns of shooting incidents and criminal activities in New York City. For additional details about the dataset, kindly refer to the attached data footnotes.

## Question 1
Question: How has the frequency of NYPD shooting incidents varied by time of day and day of the week over the years? Are there any patterns or trends in the occurrence of these incidents?

Importance: It is important to understand the temporal patterns of NYPD shooting incidents for law enforcement and community safety. Analyzing patterns based on the time of day and week can highlight trends that may not be immediately visible. For instance, if certain times are more prone to incidents, police can increase patrols or security accordingly. Temporal analysis can also help in understanding the effectiveness of crime prevention strategies over time and in making decisions based on the data for future measures from the NYPD. This approach can lead to a more proactive approach rather than reactive, potentially reducing the frequency and impact of these incidents.


<img width="792" alt="Screenshot 2023-12-05 at 3 28 16 PM" src="https://github.com/ackerber/MIST4610_Project2/assets/95188765/b79f51a1-73a3-4fe9-b75d-16a0cf5181cd">


The line chart from the first image illustrates NYPD shooting incidents by time of day, year, and borough. The data indicates that the Bronx and Brooklyn have the highest frequency of incidents, particularly during late night to early morning hours. This suggests a pattern where these hours might require heightened police attention. Also, Staten Island consistently shows the lowest incident count, indicating it may not require the same level of police security as the other boroughs. This temporal analysis can assist in assigning patrol schedules and public safety initiatives to the times when they are most needed.


<img width="792" alt="Screenshot 2023-12-05 at 3 31 10 PM" src="https://github.com/ackerber/MIST4610_Project2/assets/95188765/7e60d8fb-6d8b-454c-8365-69fc719da170">


The bar chart from the second image presents NYPD shooting incidents by month and borough. The visualization reveals that the summer months, particularly July and August, see a spike in incidents across all boroughs, with the Bronx and Brooklyn again leading in frequency. This seasonal trend could be caused due to a variety of factors, including increased social activity and gatherings during warmer months. Since there are lower incidences in colder months, it suggests a potential seasonal impact on crime rates. Law enforcement can use this information to anticipate seasonal variations in incidents and prepare accordingly, perhaps by reallocating resources during peak months to address the increased frequency of shootings.

## Question 2

Question: What are the spatial trends and hotspots of NYPD shooting incidents across different boroughs? Are there any correlations between the location descriptions and the occurrence of shooting incidents? 

Importance: Understanding the spatial distribution of NYPD shooting incidents across boroughs is critical for law enforcement to allocate resources effectively and address public safety concerns. Identifying hotspots can guide the deployment of police forces, enhancing their presence in areas prone to such incidents. Additionally, recognizing the precincts with the highest occurrence of incidents within each borough aids in targeted interventions and strategic resource allocation. 


<img width="792" alt="Screenshot 2023-12-05 at 3 17 38 PM" src="https://github.com/ackerber/MIST4610_Project2/assets/95188765/fd49108e-444f-48df-82eb-8fc7b0c0a069">


An examination of the incident counts by borough reveals that the Bronx and Brooklyn exhibit the highest number of shooting incidents, while Staten Island reports the fewest incidents. Based on the volume and the size of the data points, it is clear that more attention should be focused on these boroughs experiencing more instances of shootings. It is clear from this visualization that Staten Island is relatively safer than the other boroughs, meaning resources can be better allocated to the surrounding boroughs. 


<img width="792" alt="Screenshot 2023-12-05 at 3 18 41 PM" src="https://github.com/ackerber/MIST4610_Project2/assets/95188765/796a4917-0dc7-4c8b-ac7b-b1664f7ca53e">


The bar chart depicting the most common precincts corroborates this observation, with seven of the top 20 precincts situated in Brooklyn, and seven located in the Bronx. Furthermore, Staten Island only registers one precinct within the top 20, specifically ranking at number 18. Further analysis of these shooting incidents illustrates specific precincts serving as hotspots within the Brooklyn borough. Precincts 75, 73, and 67 emerge as the areas with the highest incidence rates within all of New York, with all three happening to be in Brooklyn, signifying a need for intensified police presence and targeted intervention strategies in these precincts. 


## Manipulation of the Data Set:
There was little need for us to manipulate the data, but some rows were removed for possible misclassification. There were two incidents that were spatially located in the middle of Manhattan but were labeled as being in the Bronx, so those were removed. We then ensured that all data points were standardized. Standardization involves transforming data into usable information for analysis. It must be quantifiable, meaningful, and interpretable data that is free of any duplicate or irrelevant entries. Inaccuracies in this process could hinder the analysis of this data set and lead to false conclusions. Additionally, we ensured that all data entries were complete and double-checked that their format was consistent throughout. 

## Tableau Packaged Workbook
The packaged workbook with the displayed visualizations is included in this repository.
