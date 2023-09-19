# Electric Vehicle Analysis
**Vince Gregoric**  
**September 19, 2023**

## Overview
This project is an exploration of how electric vehicles (EV) have changed over the past decade. It is a personal project I started as an application of the Tableau skills I learned while completing the Business Intelligence Data Analyst career path on Codecademy.com. I've been seeing a lot more EVs and EV charging stations recently, and I'm passionate about sustainability, so I thought this would make an interesting data analysis project.

The data for this projects comes from the following sources:
- [Argonne National Laboratory Light Duty Electric Drive Vehicles Monthly Sales Updates](https://www.anl.gov/esia/light-duty-electric-drive-vehicles-monthly-sales-updates)
- [US Department of Energy Alternative Fueling Station Locator](https://afdc.energy.gov/stations/#/find/nearest)
- [US Department of Energy Find a Car Power Search](https://www.fueleconomy.gov/feg/powerSearch.jsp)

The EV sales data from Argonne National Lab was obtained from [this PDF](https://www.anl.gov/sites/www/files/2023-09/Total%20Sales%20for%20Website_August2023.pdf). The [Alternative Fuels Data Center API](https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/all/) was used to access data on EV charging station locations. The data on various EV models was obtained through web data scraping (see the `data_scraping.ipynb` notebook).

## File Structure
This project contains the following files:
- **EV_charging_station_data.csv:** Data on EV charging station locations
- **EV_monthly_sales.csv:** Data on the monthly sales of EVs
- **EV_yearly_sales.csv:** The data from `EV_monthly_sales.csv`, aggregated by year to find the total yearly sales
- **electric_vehicle_data.csv:** Data on various features of different EV models
- **data_scraping.ipynb:** The Jupyter notebook used to scrape data from the US Department of Energy Find a Car Power Search
- **Electric Vehicles on the Rise.twbx:** The Tableau file where the data is analyzed and visualized
- **Electric Vehicle Dashboard.png:** An image of the final Tableau dashboard
- **README.md:** This file, containing an overview of the project
- **LICENSE.md** The license for the project
