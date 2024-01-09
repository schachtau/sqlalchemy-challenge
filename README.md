The project uses a SQLite database (hawaii.sqlite) which contains two tables- Station and Measurement. These tables are generated using SQLAlchemy, and more specifically reflection. Reflection reads the database (hawaii.sqlite) and builds the tables or metadata based on that information.

The Flask application is set up with ways to retrieve different climate data. The main ways include:

/api/v1.0/precipitation: Retrieve precipitation data. /api/v1.0/stations: Retrieve a list of weather stations. /api/v1.0/tobs: Retrieve temperature observations for the most active station. /api/v1.0/ and /api/v1.0//: Retrieve temperature statistics for a date range. Flask Routes The application provides several routes, each serving a specific purpose. The routes can be accessed by navigating to the appropriate endpoint.

/: Home route displaying available routes. /api/v1.0/precipitation: JSON representation of precipitation data. /api/v1.0/stations: JSON list of weather stations. /api/v1.0/tobs: JSON list of temperature observations for the most active station. /api/v1.0/ and /api/v1.0//: JSON list of temperature statistics for a date range. Exploratory Data Analysis The project includes exploratory data analysis, such as finding the most recent date, calculating precipitation statistics, determining the total number of stations, and analyzing the most active stations.
