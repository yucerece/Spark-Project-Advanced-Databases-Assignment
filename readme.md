
# Spark Project - Advanced Databases Assignment 

This project is developed for the Advanced Databases course at Galatasaray University, Computer Engineering Department. The project involves various data processing and analysis tasks using Apache Spark.

## Project Overview

1. **Spark Setup:** The project is executed using a Jupyter/all-spark-notebook Docker container. The container includes Apache Spark version 3.5.0 and Hadoop version 3. The container enables the use of Spark through a Jupyter notebook interface.
2. **Warm Up 1 & 2:** Basic queries were performed on the data to calculate the number of orders, products, sellers, and daily sales.
3. **Exercises 1-4:** Advanced analyses such as calculating the average revenue of orders, sellers' daily quota contributions, identifying top and bottom sellers for each product, and creating a hashed column using a custom function were performed.

## Technologies Used

- **Apache Spark 3.5.0**
- **Hadoop 3**
- **Jupyter Notebook**
- **Docker**

## Setup and Usage

### Requirements

- Docker must be installed on your system.

### Running the Project

1. **Download and Run the Docker Container:**
   ```bash
   docker pull jupyter/all-spark-notebook
   docker run -p 8888:8888 jupyter/all-spark-notebook
