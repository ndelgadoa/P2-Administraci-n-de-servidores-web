# P2-Administraci-n-de-servidores-web
La actividad es individual, pero os podéis ayudar sin copiar.
Comente todo el código para su correcta comprensión. Si quiere destacar algo, puede
responder la actividad con los puntos que considere clave o destacables.
Instrucciones de entrega:
Esta entrega se realizará mediante la plataforma Moodle y GitHub.
En el Moodle, habrá que subir un archivo .md con el siguiente nombre: DAW_
DAW_Apellido1_Apellido2_Nombre.md siguiendo el formato Markdown para explicar
los diferentes ejercicios.
En GitHub se tendrá que subir en el repositorio de la asignatura.
Se puede añadir imágenes y añadirlas en el documento.


1. Explique con sus palabras que es una petición GET, POST, PUT y DELETE,
   remarcando sus diferencias.

   - La petición GET es para hacer peticiones de recursos al servidor pero sin modificar datos del servidor.
   - La petición DELETE como su propio nombre indica permite eliminar un recurso o documento del servidor.
   - La petición POST es un metodo que se suele utilziar para formularios hmtl para modificar datos del servidor.
   - La petición PUT se utiliza para crear o reemplazar un documento del servidor.

2. Cambie del puerto 80 al puerto 4444 el servidor apache2. Muestra desde el navegador
   su funcionamiento adjuntando una captura de pantalla.
   
   ![image](https://user-images.githubusercontent.com/113515284/196519098-f8890665-8ff5-4e05-8a42-138480003748.png)
   ![image](https://user-images.githubusercontent.com/113515284/196519123-61922516-198a-4a70-a084-f25a6621da3e.png)
   ![image](https://user-images.githubusercontent.com/113515284/196519159-8ce92796-3735-4893-9d9a-e549d3de797c.png)
   ![image](https://user-images.githubusercontent.com/113515284/196519189-3ed8c8b6-9951-43c6-a136-a6b7b0c2450e.png)
   ![image](https://user-images.githubusercontent.com/113515284/196519214-c9d74150-63b1-419f-be4e-9115b0b70a5f.png)

   

   


   

   
3. Explica como activar, desactivar, reiniciar y recargar un servidor de Apache2
   explicando la diferencia entre cada uno de los comandos utilizados.
   - Activar: Activar lo que hace es iniciar el servidor
   ![image](https://user-images.githubusercontent.com/113515284/196519667-7b9371d4-a260-421d-809a-6902508e7a58.png)

   - Reiniciar:  Detiene e inicia el servidor
   <img width="315" alt="image" src="https://user-images.githubusercontent.com/113515284/196519487-55d4ef41-9ba5-4dc4-b272-e2dd6c2bea91.png">
   
   - Recargar: Recarga sin cerrar apache
   <img width="298" alt="image" src="https://user-images.githubusercontent.com/113515284/196519571-eed8de98-a1fc-4413-9d72-22edc24aca6d.png">

  - Desactivar: Desactiva servidor
  <img width="429" alt="image" src="https://user-images.githubusercontent.com/113515284/196519733-3f8dd29f-58a1-448b-b668-fb5922f7097e.png">


   
   .
4. ¿Dónde se encuentran los ficheros de configuración de Apache2?

  - Se encuentra en la carpeta conf, dentro de la carpeta en la que se encuentre instalado


   .
5. ¿Dónde se encuentran los ficheros de ejecución de Apache2?
  - En la carpeta httpd.conf
   .
6. ¿Dónde se encuentran los ficheros de monitorización de Apache2?
   - En esta ruta /var/log/apache2/access. log.
   .
7. ¿Qué es un Firewall? ¿Para que funciona? ¿Por qué es necesario?
  - Un firewall es un sistema diseñado para proteger las redes privadas del acceso no autorizado y no verificado en una conexión a Internet.
   .
8. Explica con tus palabras las diferentes partes de una URL.

  - Protocolo: Indica al navegador como tiene que acceder al recurso web
  
  - Dominio: Es el nombre de tu sitio
  
  - Puerto : Es como la puerta para acceder a los sitios web
  
  - Query:  Que se utiliza para hacer referencia a una interacción con una base de datos
  
  - Parametros: Sirven a los programadores para incluir información adicional
   .
9. Explica el funcionamiento del protocolo HTTP.
  Se basa en sencillas operaciones de solicitud/respuesta. Un cliente establece una conexión con un servidor y envía un mensaje con los datos de la solicitud.
  El servidor responde con un mensaje similar, que contiene el estado de la operación y su posible resultado.
