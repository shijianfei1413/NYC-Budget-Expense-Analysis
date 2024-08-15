# NYC Expense Budget Analysis

## Overview
This project focuses on analyzing New York City's expense budget to uncover opportunities for potential savings and efficiency improvements. Targeted at city planners, policymakers, and civic tech organizations, the analysis compares Adopted and Financial Plan expense data to assess budget execution efficiency. By identifying areas of overspending and proposing cost-saving strategies, the project aims to optimize resource allocation and improve budget planning.

## Project Documents

### 1. **Final Term Project Presentation (PDF)**
   - **Description**: This PDF presentation provides a comprehensive overview of the project, including the business use case, data source details, the analytical framework, and key findings. It serves as a high-level summary of the project and is ideal for those looking to understand the project’s objectives and outcomes.
   - **[View the Presentation](path-to-your-pdf-file)**

### 2. **Managing Data - Final Project (ZIP)**
   - **Description**: This ZIP file contains the full project materials, including datasets, code, and documentation related to the project. It covers the entire process from data extraction using the NYC Open Data API, to transformation and loading into PostgreSQL and MongoDB databases, and the development of a Flask-based API for data retrieval.
   - **[Download the Project Files](path-to-your-zip-file)**

## Key Components

### Data Source
- **NYC Open Data - Expense Budget Dataset**: The primary dataset used in this project is sourced from NYC Open Data, specifically the Expense Budget dataset. This dataset, updated every four months, provides detailed information on the city's budget expenditures.
  - **Data Access**: The dataset can be accessed through the Mayor’s Office of Management & Budget section on NYC Open Data, available in various formats including CSV and JSON.
  - **[Explore the Dataset](https://data.cityofnewyork.us/City-Government/Expense-Budget/mwzb-yiwb)**

### Analytics Framework
- **ETL Pipeline**: The project utilizes an ETL (Extract, Transform, Load) pipeline to process and clean the data. The extraction is done via NYC Open Data's API, with data transformed and loaded into PostgreSQL for structured data and MongoDB for unstructured data.
- **Data Quality**: The project emphasizes data quality dimensions such as completeness, accuracy, and timeliness, ensuring that the analysis is based on reliable and up-to-date data.

### Technologies Used
- **PostgreSQL**: For managing structured data, ensuring data accuracy and performance.
- **MongoDB**: For handling unstructured or semi-structured data, providing flexibility and scalability.
- **Flask**: A lightweight web framework used to create an API for data retrieval, enabling efficient querying of the databases.

## Conclusion
This project leverages advanced data analytics to provide insights into NYC's expense budget, offering recommendations for cost-saving strategies and efficiency improvements. The findings are intended to guide data-driven decision-making, potentially leading to better resource allocation and optimized budget planning.

## Authors
Jianfei Shi, Leyi Shi, Yumeng Tian, Ruitong Yin, Ziyue Pan

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
