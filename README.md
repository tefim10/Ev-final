# planets
Ejemplo de como subir un repositorio a Gthub

El ejercicio que deberán realizar es el siguiente:

Github
1. Entra a tu cuenta con tu usuario y contraseña
2. Entrar en la página https://github.com/OpenScienceLabs/planets 
3. hacer un fork para tu cuenta

Local (en tu computadora)
1. Crea una carpeta en tu desktop o escritorio llamado dev  (nombre acortado para development )con el comando: mkdir dev
2. Entra a la carpeta recién creada dev con el comando cd
3. Clona el repositorio planets 
Usa el siguiente comando: git clone  https://github.com/< tu-usuario-en-github >/planets
4. Crea un nuevo archivo con el editor de texto nano con el nombre < tunombre >.txt (ej: daniela.txt, horacio.txt)e
incluye 2 líneas; 1. primer nombre, 2. nombre de usuario en github.  Los pasos a seguir son:

a.  nano < tunombre >.txt (incluye las líneas con los datos de arriba y despúes guardalo)

5. envíalo al staging área con el comando: git add < tunombre >.txt (ejemplo: git add daniela.txt)

6. Haz un commit del archivo con el comando: git commit -m "evaluación final de < tunombre >" 

7. Luego envía los cambios hacia el repositorio remoto en GitHub haciendo push realizando el comando : git push  origin master.

8. Abrir un pull request desde tu cuenta a Open Science Labs.

