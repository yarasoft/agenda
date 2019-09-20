<<<<<<< HEAD
Agenda Versión Node para crear la base de datos entra a c:/archivos de programa/mongo y ejecuta mongo.exe:
=======
Agenda
Versión Node
para crear la base de datos entra a c:/archivos de programa/mongo y ejecuta mongo.exe:
>>>>>>> 648e2599c7999155e79f410daec7667c59c8cd5b

despues inserta el siguiente comando:

use agenda_db

siguiente a eso inserta este comando:

db.usuarios.insertMany([{ email: 'demo@mail.com', user: "demo", password: "123456"}, { email: 'jose@mail.com', user: "jose", password: "123456"}])

luego ejecuta nodejs en la carpeta server en el archivo index.js ejecuta por consola:

node index.js

por ultimo te saldra un mensaje diciendo server is listening on port 3000 y conectado a mongodb, luego de esto pon la siguiente direccion en el navegador.

<<<<<<< HEAD
localhost:3000/index.html
=======
localhost:3000/index.html
>>>>>>> 648e2599c7999155e79f410daec7667c59c8cd5b
