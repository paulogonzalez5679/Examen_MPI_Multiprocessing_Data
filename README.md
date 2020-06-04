# GonzalezPaulo_Examen_MPI_Multiprocessing

# Multiprocessing

Se toma en cuenta el numero de procesadores que existen dentro del servidor y se ejecuta, en mi caso seleccione solo 2 a pesar de que tiene 4 por ello el cambio no es muy notorio, en el proces se reutiliza lo que es el secuencial con el fin de obtener el array de los numero y dividir para la cantidad de procesadores.

python  GonzalezPaulo_Examen_Multiprocessing.py

Resultados:

Para la prueba del programa se utiliza 1000 datos por cuestiones de tiempo pero se la evidencia de una reduccion de de 20s

Imagen de evidencia:

https://drive.google.com/file/d/1mlpP0Lb5aY-EQP4n53DA6y6xIty0BtVP/view?usp=sharing 

Results are correct!

Sequential Process took 0.140 ms with 1000 items

Parallel Process took 0.120 ms with 1000 items


# Para la ejecucion del MPI
mpiexec python GonzalezPaulo_Examen_MPI,py
