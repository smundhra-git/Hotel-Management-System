This is a simple hotel management system that allows users to create new rooms, view all rooms, check-in, check-out, and perform data analysis. The system utilizes the MySQL database to store information about the rooms and customers. The system also uses Python and the mysql-connector, pandas, and matplotlib libraries to perform various tasks.

The system has a main menu that allows the user to select from the following options:

Create New Room: Allows the user to create a new room in the hotel.
Show All Rooms: Shows all the rooms in the hotel and their information.
Check-In: Allows the user to check-in a customer into a room.
Check-Out: Allows the user to check-out a customer from a room.
Data Analysis: Allows the user to view various data analysis charts such as room number and charges chart, room number and number of times booked chart.
Exit: Exits the system.
The system also has different functions separated in different python files: RoomFunctions.py, CheckInCheckOutFunctions.py, and DataAnalysis.py. Each file contains functions for their respective names.

Please make sure the mysql-connector, pandas, and matplotlib are installed in your system before running the code. Also, please update the database credentials (host, user, passwd) to match your database setup.
