# AirBnB_Power BI_Project

## Project: Analysis of Airbnb Data Using Power BI

Airbnb, headquartered in San Francisco, California, operates a popular online marketplace specializing in short-term accommodations and experiences. Established in 2008 by founders Brian Chesky, Nathan Blecharczyk, and Joe Gebbia, the name Airbnb is derived from its original moniker, AirBedandBreakfast.com. iVision analytics firm has been provided with datasets related to Airbnb listings and reviewer scores worldwide. The objective is to gain a deeper understanding of Airbnb's operations and draw meaningful insights from the data. As a BI Analyst at iVision, your role is to create informative reports by conducting a thorough analysis of the data using powerful tools like PowerBI.

## Table of Contents
- [Description](#description)
- [Data Description](#data-description)
- [Software/Tools](#softwaretools)
- [Business Objective](#business-objective)
- [Project Goals](#project-goals)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Data Description
- The necessary data and data dictionaries are available as CSV files.
- The Reviews (Reviews.csv) dataset contains information about reviews left for Airbnb listings.
- The Listings (Listings.csv) dataset contains all relevant details about the listed stays.
- Comprehensive descriptions of each column can be found in their respective data dictionary files (Listings_data_dictionary.csv and Reviews_data_dictionary.csv).

## Software/Tools
- Power BI

## Business Objective
The primary objective is to analyze Airbnb data to reveal insights into user experiences and satisfaction levels with the numerous listed stays, all accomplished using Power BI.

## Project Goals
- Assessing District Location Scores: The aim is to pinpoint the location in the district with the least favorable location scores.
- Examining Host Response Time Impact: The goal is to delve into the relationship between host response times and the overall ratings of Airbnb listings, providing valuable insights.
- Visualizing Airbnb Listing Prices: The objective is to create visual representations of Airbnb listing prices across different cities and summarize any noteworthy trends or variations.
- Analyzing Composite Scores: The task involves creating a composite score that integrates check-in experience and host communication for various districts with subsequent analysis and insights.
- Calculating Listing Age and Host Tenure: This objective entails computing the age of Airbnb listings and identifying hosts who have accumulated more than ten years of hosting expertise.
- Property Type Price Analysis: The task involves the creation of a visual tree map that displays average prices for various room and property types with specific attention given to the property type associated with the highest prices 
  for entire places.
- Crafting a Comprehensive City Insights Report: This objective entails the creation of a comprehensive report that presents listing prices, guest ratings, and visitor trends for multiple cities, with a particular focus on assessing 
  changes in visitor trends in 2020 in contrast to earlier years.

## Installation
   - Clone the repository:
     git clone https://github.com/shishir1991/AirBnB_Power-BI_Project.git
   - Open the Power BI report file (Shishir kherod_ABADS_B11.pbix) in Power BI Desktop.
   - Ensure that you have the necessary data sources available (e.g., Listings_data_dictionary.csv, Reviews_data_dictionary.csv).

## Prerequisites
   - Power BI Desktop
   - Data source files (Listings_data_dictionary.csv, Reviews_data_dictionary.csv)

## Usage
   1. Open the Airbnb_Data_Analysis.pbix file in Power BI Desktop.
   2. Navigate through the different pages of the report to explore various insights:
     
   - Overview: Summary of key metrics and KPIs
   - District Location Scores: Analysis of the least favorable location scores by district
   - Host Response Time Impact: Relationship between host response times and overall ratings
   - Listing Prices: Visualization of listing prices across different cities
   - Composite Scores: Composite score analysis integrating check-in experience and host communication
   - Listing Age and Host Tenure: Age of listings and hosts with over ten years of experience
   - Property Type Price Analysis: Tree map of average prices for various room and property types
   - City Insights Report: Comprehensive report on listing prices, guest ratings, and visitor trends, with a focus on 2020 changes

## Screenshots
   ### District Location Scores
     
   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/263791e0-3034-44e9-9d30-6f10b742fd7d)

   - As per the Stacked column  chart, the statistics shows that Hong Kong city has the least favourable location score with total of just 36108.
   - Also Paris city has the most favourable location score with the total of 464616.
     
   ### Host Response Time Impact

   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/e87e5f40-0460-449e-8267-4186dcf96a59)

   - The Clustered Column Chart here shows that 83K of the host response time is within an hour.
   - Also the host with maximum review score rating of 66K response within an hour. So customers prefer host which response quickly to their queries.

   ### Listing Prices

   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/38073107-738e-43fc-91ff-7a4c6311f2d4)

   - According to line chart analysis Rome city has the best affordable price as compared to others with average price of $105.11

   ### Analysing Composite Scores

   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/98893b15-294f-4316-b9fd-a6867fce47f0)

   - According to the stacked column chart here we can see that the Staten Island district has the highest average Review score for communication as well as for check-in which states that host of this district are much interactive in 
     responding to queries and care about a comfortable check-in of their customers.

   ### Listing Age and Host Tenure

   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/b127f65b-15b1-41b7-896e-8945e9422335)

   - The respective chart shows here the statistics of total number of listing age and host tenure in years. 
   - Here 15662 no. of host have 11 years of hosting tenure which is the maximum of all other hosts whereas only 65 hosts having 15 years of hosting tenure.

   ### Property Type Price Analysis

   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/b37cb56f-3e35-47c0-9155-2cb255d1085f)

   - The task involves the creation of a visual tree map that displays average prices for various room and property types with specific attention given to the property type associated with the highest prices for entire places.

   ### City Insights Report

   ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/96de63d2-c14c-48db-bcd7-111b3f47c7e0)

## Power BI Report

  ![image](https://github.com/shishir1991/AirBnB_Power-BI_Project/assets/157515610/8883663d-2953-43f4-a4a2-ca14172dfc98)

## Contributing
   Contributions are welcome! Please follow these steps to contribute:
  - Fork the repository.
  - Create a new branch (git checkout -b feature-branch).
  - Make your changes.
  - Commit your changes (git commit -m 'Add new feature').
  - Push to the branch (git push origin feature-branch).
  - Create a new Pull Request.

## License
   This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
   Created by Shishir Kherod - feel free to contact me at shishirdma@gmail.com.























