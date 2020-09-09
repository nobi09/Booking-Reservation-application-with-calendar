Installation
The online booking calendar requires a single table in an SQL database. The database settings: servername, username, password, database name, and table name are configured in the "config.php" file. After configuring the database settings in "config.php" file, run "install.php" which will create the requried table and columns to the database.

For very the basic use, it is necessary to only modify the items to be booked. The items are listed in the "index.php" file starting from row 97. To add a custom item, change the "value" field of the radio button to the name of the item. Add also a label next to the radio button.


L' applicazione necessita soltanto di una tabella in database SQL. Le impostazione del tabase possono essere cambiate a proprio piacimento nel file chaiamato "config.php". Dopo aver configurato il database, bisogna eseguire il file "install.php" il quale ha la funzione di creare la tabella e le sue colonne di salvataggio.
inizialmente, solo il valore "meeting room" è presente nell' aaplicazione ma è possibile introdurne degli altri dalla 97esima riga. Queste si presenteranno sottoforma di radio buttons, i quali valori possono essere cambiati in base alle proprie esigenze.