Thai-railway-pj2

Section: 2

Group: 13

Member:

Miss  Supithcha    	Jongphoemwatthanaphon  	 6488045

Miss  Kanita		Karunkittikun  	         6488049

Miss  Sasasuang  	Pattanakitjaroenchai     6488052

Miss  Nisakorn 		Ngaosri                  6488226

Setting MYSQL Server
1. Use MySQL Workbench to access the MySQL server for managing the relational database.
2. Open the "railwayticket" sql file on the program.
3. Go to the "server" on navigation bar > click "Users and Privilleges"
4. Select user name to set the schema privilege, click "Add Entry" > Select "railwayticket" > Allow SQL operations (SELECT, INSERT, UPDATE, DELETE) > click Apply
5. Change MYSQL_HOST, MYSQL_USERNAME, MYSQL_PASSWORD, MYSQL_DATABASE on .env file in Visual Studio Code

How to run our codes
1. Go to the Visual Studio Code 
2. Open the folder "sec2_gr13_pj2_ID045_049_052_226" on Visual Studio code
3. Open the terminal > click "Split Terminal"
**NOTE: You must use 2 terminal for run our application.*** 
(One terminal for task2_db.js, and another for route_ui.js)
4. Install node mon using "npm install nodemon" command in both first terminal and second terminal.
5. Install node mon using "npm install node_modules" command in both first terminal and second terminal.
6. In first terminal using "cd backend_db" command in terminal.
7. In second terminal using "cd front_ui" command in terminal.
8. Use "npm start" command in both first terminal and second terminal.
9. Open the website base on port that server listening. (For our surver listening on localhost:3030)
10. Welcome to our web application
