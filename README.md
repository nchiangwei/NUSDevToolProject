# NUS-devtool2-Project

Not included are:

Database connection parameters. You will need to create a .env file in the /backend folder to contain connection parameters for your MySQL database. The .env_sample file contains a list of the parameters you need to set.
Database server. The backend server uses the node.js mysql module to connect to a MySQL server. The MySQL server itself is not provided, but sample data is available in the /database_sample folder.
Node modules. 
You will need to initialise a node.js project in the /backend folder:
      
      
  npm init                                                    /* initialise a new node.js application */
  
  npm install --save mysql express body-parser cors dotenv    /* install the modules required by the backend */
