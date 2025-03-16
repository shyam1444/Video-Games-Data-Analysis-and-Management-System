# Video Games Data Analysis and Management System

This project is a Python-based application designed to visualize and manage a comprehensive dataset of video game information. By integrating Python with MySQL, the system allows users to efficiently analyze and interact with extensive video game data.

## Features

- **Data Visualization**: Utilizes Python libraries to create insightful visual representations of the video game dataset.
- **Database Management**: Employs MySQL to handle data storage, retrieval, and manipulation, ensuring efficient data management.
- **Comprehensive Dataset**: Includes a vast collection of video game data, facilitating in-depth analysis and exploration.

## Requisites

To set up and run this project, follow these steps:

1. Copy the code into the Jupyter Notebook.
2. Download XAMPP and run it while keeping the tab open.
3. Open PHPMyAdmin (localhost) from XAMPP.
4. Import the database into localhost.
5. Add each section of code in separate cells within the Jupyter Notebook.
6. Run the "Modules and Packages" cell first, followed by the remaining code in each subsequent cell.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/shyam1444/Video-Games-Data-Analysis-and-Management-System.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Video-Games-Data-Analysis-and-Management-System
   ```

3. **Install Required Python Libraries**:

   Ensure you have `pip` installed. Then, execute:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the MySQL Database**:

   - Install MySQL Server if it's not already installed.
   - Create a new database named `video_games_db`.
   - Import the `games.csv` data into the `video_games_db` database.

5. **Configure Database Connection**:

   Update the database connection settings in the Python scripts to match your MySQL configuration (e.g., username, password, host, and database name).

## Usage

After completing the installation steps:

1. **Run the Application**:

   Execute the main Python script to start the application:

   ```bash
   python main.py
   ```

2. **Explore Data**:

   Use the application's interface to visualize and analyze the video game data.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. 

## Acknowledgements

Special thanks to all contributors and the open-source community for their invaluable resources and support.
