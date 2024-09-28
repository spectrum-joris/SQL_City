# Welcome to **SQL CITY** # 
## the game ##

The **purpose** of this game is for students to apply DML SQL queries. Below you find instructions to use this game. 

--- 

| developed |  |
| -------------- | -------------- |
| by | Joris Petillion, teacher "informatics: science and applied" |
| for | Het Spectrum, Secondary School in Gent |

---

**© Het Spectrum, Gent**
![Spectrum logo](https://scholen.stad.gent/sites/default/files/styles/logo_desktop/public/school/logo/desktop/Spectrum_WIT.png?itok=XurlfKmP)

---

In short, this is how it's being played: 
- 4 pupils/teams and a teacher are connected to the same database 
- the pupils populate the tables of the database so each of them reaches a target
- the teacher is the "disaster manager" (of course (s)he is 🤣), and deletes data in tables from the database, imitating disasters such as theft, lost crops, murder, earthquakes, ... causing buildings, people, money or food to disappear from their respective tables 
- The students/teams then have to repair the situation as quickly as possible, using their SQL skills. They should reach their ratio targets asap

---

You are free to copy and adjust this code as long as you ==refer to our school== in the Readme.md file of your project as follows: *"This game is based on its original by Het Spectrum Middelbaar Onderwijs, Gent, Belgium"*

---

# SQL City • The Game
*For 4 roles and 1 teacher*

Welcome to SQL City, a virtual city where you and your teammates hold the reins! Each player is assigned a specific role in the city and must perform their tasks well to help the city thrive. But watch out, disasters may strike and put the city in danger! It’s up to you to work together, manage the right data, and restore the city when the teacher (the “Disaster Manager”) causes chaos.

## Goal of the Game:
Manage the city by adding and modifying data in a database using SQL queries. We use HTML, CSS, and JavaScript to display information about the city and its inhabitants in the web browser. You must ensure that the ratios in the city are balanced, despite the disasters caused by the teacher.

**Work together to manage SQL City, respond to disasters, and make sure the city's ratios are correct!**

## Roles and Responsibilities:
1. **Banker:**
   - Manages the inhabitants' bank accounts and the city's balance.
   - **Ratio:** Each inhabitant must have at least 10 units of money, and the city must have at least 1000 units of balance per inhabitant.

2. **Shopkeeper:**
   - Manages the city's food supply.
   - **Ratio:** There must be at least 20 units of food available per inhabitant.

3. **Mayor:**
   - Manages the city's inhabitants.
   - **Ratio:** There must be enough housing for all inhabitants (1 house per inhabitant).

4. **Developer:**
   - Manages the city's buildings and infrastructure.
   - **Ratio:** Each building must house 5 to 10 inhabitants, and there must be 1 unit of infrastructure per building.

## What do you need to do?
1. Create tables in the database to manage your role. You will have access to a CleverCloud database where you can create and edit these tables.
2. Populate the tables with initial values (the city's basic data), such as the first inhabitants, the city's balance, food supply, buildings, etc.
3. Use SQL queries to add, edit, and display data in your role.
4. Respond to disasters: The teacher may cause disasters such as failed harvests, disease epidemics, earthquakes, and cybercrime. These will affect the data in your tables, and you must restore the ratios.

## Disasters:
The teacher is the “Disaster Manager” and can trigger the following disasters:
- **Failed Harvest:** Reduces the food supply.
- **Disease Epidemic:** Reduces the population.
- **Earthquake:** Destroys buildings and infrastructure.
- **Cybercrime:** Reduces the money in the bank.

### Key Ratios to Maintain:
1. **Inhabitants / Food:** 20 units of food per 1 unit of inhabitants.
2. **Inhabitants / Money:** 10 units of money per 1 unit of inhabitants.
3. **City / Money:** The city must have 1000 units of money in its balance.
4. **Buildings / Capacity:** 1 unit of buildings can accommodate 0.5 unit of inhabitants.
5. **Building Capacity:** Each building must house 5 to 10 units of inhabitants, but the cost is 1000 money units per building capacity.
6. **Infrastructure:** There must be 1 unit of infrastructure per 1 building.

Your task is to restore the correct ratios in the city as quickly as possible!

---

# How to use this project #

1. install dependencies using the CLI command **npm install** (you can see what will be installed in the project's package.json file)
2. make the program run by using **npm start**, and stop using **CTRL + C**
3. **connect** with a cloud-based database (we use clever-cloud): make sure you enter your own database connection credentials in the .env file
4. optional: enter your db connection credentials in a local MySQL database (Workbench or Sequel for instance) to see your tables and data change instantly
5. enter your disaster or repair **queries** in your SQL interface (we use VSC, which connects to the same database, using the same credentials) 
6. see the **output** of your game here: http://localhost:3000/index.html, or in JSON format via http://localhost:3000/api/ratios # SQL_City
