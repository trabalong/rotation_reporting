# Cálculo de Rotación de Plantilla
## Intro
En este proyecto, limpiare y transformaré una BBDD inventada de empleados para su correspondiente cálculo de rotación.
## Data
- `employees.csv` Plantilla parcial de una empresa.
- `listado.csv` BBDD de todos los work places y sus responsables.
- `tipo_contrato.csv` BBDD con los códigos y tipos de contrato.
- `emails.csv` BBDD con todos los emails corporativos.
- `cleaned_data.csv` BBDD de la plantilla limpia y transformada.
## Notebook Main
- `cleaning_data.ipynb` Código donde se limpia y transforma los datos usando librerías Pyspark, exportando la BBDD limpia para su cálculo.
- `reporting_rotation` Código que calcula la rotación de plantilla en un periodo establecido.
## Resources
- https://pandas.pydata.org/
- https://docs.python.org/3/library/warnings.html
- https://docs.python.org/3/library/datetime.html
- https://docs.python.org/3/library/itertools.html
- https://spark.apache.org/docs/2.4.0/api/python/pyspark.sql.html