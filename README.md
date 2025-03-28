# Walmart Retail Sales Analysis 2012-2015


## Description
This project performs an analysis on Walmart's retail sales data spanning from 2012 to 2015. The data includes various attributes such as sales, profits, shipping costs, customer segments, and product categories. The project performs the following:
- Cleans and transforms the data for analysis.
- Inserts the cleaned data into a MySQL database.
- Runs SQL queries to analyze sales trends by state and product profitability by region.
- Visualizes the results using `matplotlib` and `seaborn`.

## Getting Started

### Prerequisites
To run this project, you will need the following software:

- **Anaconda**: An open-source distribution of Python and R that simplifies package management and deployment. Download it from [here](https://www.anaconda.com/products/individual).
  
- **Jupyter Notebook**: A web-based application that allows for the creation and sharing of documents that contain live code, equations, visualizations, and narrative text.     It is included with Anaconda, but you can also install it separately via pip:
    ```bash
          pip install notebook
-  MySQL: A relational database management system used to store and manage the data. Download MySQL from here.
-  MySQL Connector for Python: A library to connect MySQL with Python. Install it using:
          pip install mysql-connector-python

### Installing
  Follow these steps to set up the environment and get the project running:

  1. **Install Anaconda:**
      Go to the Anaconda Downloads Page.
      Choose the appropriate version for your operating system (Windows, macOS, or Linux).
      Download and run the installer. Follow the on-screen instructions to complete the installation.
  2. **Install Jupyter Notebook:** Jupyter Notebook is included with Anaconda, so you don’t need to install it separately. To launch Jupyter:
      Open Anaconda Navigator (Windows) or launch it from Applications (macOS).
      Click Launch under Jupyter Notebook.
      Alternatively, you can launch Jupyter from the command line:
          jupyter notebook
  4. **Install MySQL Workbench:** To manage your MySQL databases, you'll need MySQL Workbench:
      Go to the MySQL Workbench Download Page.
      Download and install it based on your operating system.
  5. **Install MySQL Connector:** To connect Python to MySQL, install the mysql-connector-python package:
           pip install mysql-connector-python
  6. **Ensure Database Setup:**
      Before running the project, make sure your MySQL server is running locally and that you've created a database for this project. For example:
          CREATE DATABASE 1202project4;


### Running the Code
  Open Jupyter Notebook and open the .ipynb file or script from your project directory.
  Run the script step by step to load the data, clean it, insert it into the MySQL database, and execute SQL queries.
  The script will output a graph showing the sales trends across different states and a bar chart displaying profits by product category and region.

### Running the Tests (Optional)
  (Optional if you're testing) 
  If you wish to test the different components of the code (e.g., MySQL connection, data loading, etc.), you can follow the test instructions provided above. It ensures the    project is running smoothly before deployment.

### Breakdown of Tests
  Test MySQL Connection: Checks if the connection to the MySQL server is successful.
  Test Data Insertion: Verifies if the data was inserted correctly into the walmartretailsales table.
  Test Sales Growth Query: Ensures the sales query returns correct data for each state and year.
  Test Product Profit Query: Verifies the profitability of products by region.

### Deployment
  Once you’ve tested everything locally and are ready to deploy:
  Deploying on a cloud server: You can deploy this on platforms like AWS, Heroku, or DigitalOcean.
  Automate the process: Set up a cron job or use a cloud service for scheduled data processing if you need this to run periodically.
  Visualizations: For better user experience, consider deploying the visualizations on a web platform (e.g., Flask/Django with frontend charts).


### Author
  Sakeena Raza
  Email: your.email@example.com
  LinkedIn: 

### License
  This project is licen sed under the MIT License - see the LICENSE.md file for details.

### Acknowledgements
  Pandas: For data manipulation and analysis.
  Matplotlib/Seaborn: For data visualization.
  SQLAlchemy: For SQL database interaction.
  MySQL: For managing the database.
  Anaconda: For providing the environment that integrates Python and its dependencies.
