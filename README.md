# Estrucutras-de-datos-y-sus-procesamientos
Repositorio escolar
Ventajas comparativas de las estructuras de datos en Python
1. Listas (list)

Características:

Estructura ordenada y mutable.

Permite elementos duplicados.

Se accede a los elementos por índice.

Ventajas:

Ideales para colecciones dinámicas donde se necesitan cambios frecuentes (agregar, eliminar, reordenar).

Compatibles con la mayoría de las operaciones de Python y librerías externas.

Soportan slicing (cortes de segmentos de la lista).

Casos de uso:

Almacenar registros temporales.

Manejar colecciones ordenadas de datos (ej. carrito de compras, tareas pendientes).

2. Tuplas (tuple)

Características:

Estructura ordenada e inmutable.

Permite elementos duplicados.

Se accede a los elementos por índice.

Ventajas:

Más ligeras que las listas (mejor rendimiento para lectura).

Útiles para representar datos que no deben modificarse (seguridad e integridad).

Pueden usarse como llaves de diccionarios (hashables).

Casos de uso:

Coordenadas (x, y).

Registros fijos (ej. fechas, datos constantes).

3. Diccionarios (dict)

Características:

Colección no ordenada (a partir de Python 3.7 mantiene orden de inserción).

Estructura de pares clave-valor.

Claves únicas, valores pueden repetirse.

Ventajas:

Búsqueda rápida de datos a través de su clave.

Muy flexibles para representar relaciones entre datos.

Base para estructuras más complejas como JSON o DataFrames.

Casos de uso:

Bases de datos simples.

Configuraciones, catálogos, inventarios.

4. Conjuntos (set)

Características:

Colección no ordenada, sin elementos duplicados.

Permite operaciones matemáticas de conjuntos (unión, intersección, diferencia).

Ventajas:

Ideal para eliminar duplicados.

Útil para comparar colecciones.

Operaciones muy eficientes para pertenencia y relaciones entre conjuntos.

Casos de uso:

Filtrar elementos únicos.

Encontrar coincidencias o diferencias entre colecciones de datos.
