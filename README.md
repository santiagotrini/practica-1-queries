# Practica 1 - Queries

## Instrucciones de instalación

1. Instalar MySQL / MariaDB. En Termux `pkg install mariadb`.
2. Asegurarse de poder ejecutar `mysql` en la terminal. En Termux `mysqld_safe &` y luego `mysql`.
3. Clonar este repo `git clone https://github.com/santiagotrini/practica-1-queries`.
4. Cambiar al directorio del repo `cd practica-1-queries`.
5. Crear la base de datos `mysql < db_schema.sql`.
6. Poblar la base de datos `mysql < db_data.sql`.
7. Logearse a la base de datos `mysql practica_1`.

## Ejercicios

1. Buscar el gobernador de Neuquén.
2. Buscar la capital de Misiones.
3. Dar una lista de todas las provincias con más de un millón de habitantes.
4. Dar una lista de todas las provincias con su densidad de población.
5. ¿De qué provincia es gobernador Omar Perotti?
6. Listar solamente las provincias, sin incluir la Ciudad Autónoma de Buenos Aires.
7. Buscar las provincias que empiecen con "San" o "Santa".
8. Buscar las provincias que tengan entre 100000 y 200000 kilómetros cuadrados.
9. Buscar los gobernadores que tengan apellido que comience con "K".
10. Listar las provincias y ordenarlas por cantidad de habitantes.
11. Buscar la provincia más pequeña.
12. Buscar las provincias cuya capital se llame igual que la provincia.
13. Buscar la provincia más joven.
14. Dar la superficie total de la Argentina.
15. Dar la población total de la Argentina.
16. Listar todas las provincias indicando: nombre, superficie y porcentaje de superficie total del país que ocupa.
17. Listar las provincias autónomas desde el siglo XIX.
18. Contar la cantidad de provincias.
19. ¿Cuántos gobernadores llamados Gustavo hay?
20. ¿Cuáles son las capitales de las provincias de Cuyo?
21. Dar una lista con todas las provincias indicando hace cuantos años son autónomas.
22. Listar las 23 provincias de la Argentina anteponiendo "Provincia de ". Por ejemplo en vez de escribir "Buenos Aires" debe decir "Provincia de Buenos Aires".
