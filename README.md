# MySQL Sakila database

Sakila MySQL database script plugin for Magic that installs the Sakila database into
your _"/etc/mysql/templates/"_ folder for you. Notice, this plugin does _not_ create
the database for you, or execute the SQL script in any ways, since that requires a valid
MySQL connection, which we cannot determine with certainty that you actually have.

## Installation

Install this module in your Magic backend, open up SQL Studio, load the sakila script,
and execute it towards a valid database MySQL connection.
