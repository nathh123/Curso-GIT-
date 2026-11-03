Práctica: Creación de un repositorio con Git
1. ¿Qué aprendí del curso?
Aprendi que existe una terminal por default en mi laptop, y que sirve y tiene diferentes funcionalidades, que existen ciertos comandos que ayudan a la creacion de los repositorios en git.
 2. Comandos utilizados

Durante la práctica utilicé los siguientes comandos:

- git --version: comprobar que Git estuviera instalado.
- git config --global user.name "Nat": configurar el nombre del usuario.
- git config --global user.email "natalyhernandezherrera1@gmail.com": configurar el correo electrónico.
- git config --global -l: verificar la configuración de Git.
- cd C:\Users\hp\git\Folder: acceder a la carpeta del proyecto.
- git init: inicializar el repositorio local.
- git status: consultar el estado de los archivos.
- git add .: preparar los archivos para registrarlos en Git.
- git commit -m "Primer commit": guardar los cambios en el historial del repositorio.

 3. Estructura del proyecto

El proyecto contiene los siguientes elementos:

- CSS/: carpeta para los archivos de estilos.
- JS/: carpeta para los archivos JavaScript.
- video.html: archivo HTML de la página web.
- README.md: documento con la descripción de la práctica.

4. Dificultades encontradas y soluciones

Durante la práctica encontré un mensaje que indicaba que la carpeta actual no era un repositorio de Git. Para resolverlo, volví a ejecutar el comando git init en la carpeta del proyecto.
al mismo tiempo tuve dificultades en la ruta para agragar mis documentos, ya que copiaba la ruta manualmente, lo resolvi copiando desde la ruta
También observé que Git mostraba mis carpetas y archivos como elementos sin seguimiento (untracked files). Esto significa que todavía no estaban agregados al control de versiones. Para solucionarlo, utilicé git add . y después registré los cambios con git commit.

 5. Conclusión

Esta práctica me permitió conocer los comandos básicos de Git y comprender cómo se inicializa un repositorio, cómo se identifican los archivos pendientes y cómo se registran los cambios de un proyecto.

Además, aprendí la importancia de documentar el trabajo mediante un archivo README para facilitar la comprensión del proyecto.

