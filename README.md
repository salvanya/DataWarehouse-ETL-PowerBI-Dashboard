# ETL and Dashboard for TradeProd Data Warehouse

This repository contains a set of tools and files required to perform Extraction, Transformation, and Loading (ETL) from the public TradeProd database to a star-modeled Data Warehouse. The ETL process is carried out using Microsoft SQL Server Integration Services (SSIS) through Visual Studio Code. Additionally, it includes the creation of an interactive dashboard using Power BI to effectively visualize the data stored in the Data Warehouse.

## Repository Contents

- **Cotizacion_dolar.csv**: File providing regularization of sales prices in different locations, expressed in US dollars.

- **Creacion Data Warehouse.sql**: SQL script defining the star-shaped structure of the Data Warehouse, establishing the foundation for optimized data storage.

- **Dashboards.pbix**: Power BI files containing visually appealing and functional dashboards for exploring and analyzing data stored in the Data Warehouse.

- **ETL.dtsx**: SSIS package that performs the ETL process, extracting data from the TradeProd database, transforming it as needed, and loading it into the Data Warehouse.

## Usage Instructions

1. **Cotizacion_dolar.csv**: This file is used to keep sales prices in dollars up to date. It is recommended to review and update this file periodically to reflect changes in exchange rates.

2. **Creacion Data Warehouse.sql**: Execute this script on your SQL Server instance to create the star-modeled structure of the Data Warehouse.

3. **ETL.dtsx**: Open this SSIS package in Visual Studio Code to customize the ETL flow according to the specific needs of your environment.

4. **Dashboards.pbix**: Open these files in Power BI to visually explore the data stored in the Data Warehouse and gain meaningful insights.



## License

This project is under the [MIT License](LICENSE).

