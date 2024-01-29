<br />
<div align="center">


<h3 align="center">Optimizador de Puntos de Recogida</h3>

  <p align="center">
    Implementacion de algoritmos de Machine Learning para encontrar la mejor ruta de recogida de ciertos puntos
    <br />
    <br />
    <br />
  </p>
</div>

## Tabla de Contenido

- [Acerca del Proyecto](#star2-acerca-del-proyecto)
    * [Tecnologías Usadas](#space_invader-tecnologías-usadas)
- [Descripción General](#dart-descripción-general)
    * [Caso de Uso](#dart-caso-de-uso)
- [Contacto](#handshake-contacto)

## Acerca del Proyecto
El proyecto "Optimizador de Puntos de Recogida" se enfoca en la optimización del proceso de recogida de casas mediante el uso de técnicas avanzadas de aprendizaje automático. La meta principal es encontrar la distribución más eficiente de puntos de recogida para un conjunto dado de casas, minimizando la distancia total recorrida por los vehículos de recogida.
# Tecnologias Usadas
* Python: Lenguaje de programación principal para el desarrollo del proyecto, proporcionando flexibilidad y eficiencia en el manejo de algoritmos.

* Folium: Biblioteca de Python que facilita la visualización de datos geoespaciales mediante mapas interactivos. Se utiliza para mostrar de manera intuitiva la distribución de puntos de recogida y casas en un mapa.

* scikit-learn (sklearn): Biblioteca de aprendizaje automático en Python, utilizada para implementar algoritmos de clustering que agrupan las casas en regiones para la asignación eficiente de puntos de recogida.

* osmnx: Herramienta que facilita la recuperación y análisis de datos espaciales relacionados con la red de carreteras. Es utilizado para obtener información detallada sobre las rutas y distancias entre diferentes puntos.

* networkx: Biblioteca de Python para la creación, manipulación y estudio de estructuras, dinámicas y funciones de redes complejas. Se emplea para modelar y analizar la red de carreteras y facilitar la planificación de rutas eficientes.

## Descripcion General
### Caso de Uso
El "Optimizador de Puntos de Recogida" se encuentra diseñado para mejorar la eficiencia en la logística de recogida de casas. Este sistema utiliza algoritmos genéticos y de clustering, respaldados por técnicas de aprendizaje automático, para planificar de manera óptima la ubicación de los puntos de recogida.

* Configuración Inicial: El Administrador del Sistema ingresa al sistema y configura parámetros como el número máximo de puntos de recogida, restricciones de capacidad de los vehículos, etc.

* Carga de Datos: Se introduce la información de las casas, sus ubicaciones geográficas y cualquier restricción especial en el sistema.

* Aplicación de Algoritmos Genéticos y de Clustering: El sistema aplica algoritmos genéticos para encontrar la mejor combinación de ubicaciones para los puntos de recogida, considerando la variabilidad a lo largo de las generaciones. Se emplean algoritmos de clustering para agrupar las casas en regiones cercanas, facilitando la asignación eficiente de puntos de recogida a cada grupo.

* Generación de Rutas Optimizadas: Con base en los resultados de los algoritmos, se generan rutas optimizadas para los vehículos de recogida, minimizando la distancia total a recorrer.

* Visualización en el Mapa Interactivo: El sistema utiliza Folium para generar un mapa interactivo que muestra la distribución de las casas, puntos de recogida y las rutas optimizadas.

* Revisión y Aprobación: El Administrador del Sistema revisa las rutas propuestas y, si es necesario, realiza ajustes manuales. Una vez aprobadas, las rutas optimizadas son asignadas a los Operadores de Recogida.

* Ejecución de Recogida: Los Operadores de Recogida siguen las rutas asignadas para recoger las casas, siguiendo la planificación optimizada.

* Monitoreo y Retroalimentación: Durante la ejecución, el sistema monitorea el progreso y recopila datos sobre la eficiencia de las rutas. Se recopila retroalimentación de los Operadores de Recogida para posibles mejoras futuras.

## Contacto
santiagovl0308@gmail.com 
