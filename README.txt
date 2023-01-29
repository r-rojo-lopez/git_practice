####################################################
Pasos para crear un repositorio en local y en GitHub
####################################################

1. Crear la carpeta que contendrá los elementos del proyecto.

2. (A revisar):
	2.1. git init
	2.2. echo "Hello Git and GitHub" >> README.txt
	2.3. git add README.txt
	2.4. git commit -m "First commit"
	
3. Crear el repositorio en GitHUb:
	3.1. Click "New repository",
	3.2. Dar nombre al repositorio,
	3.3. git remote add origin https://github.com/r-rojo-lopez/git_practice.git
	3.4. git push -u origin master
	3.5. Tras el paso 3.4. puede aparecer un error tras pedir la contraseña: darla está obsoleto. Para solucionarlo se debe introducir el token. Para generar un token, ver este vídeo: 
	https://www.youtube.com/watch?v=m5SChqEi314
	3.6. Tras realizar el paso 3.5. puede aparecer un nuevo error "your push would publish a private email address". Para solucionarlo, ver:
	https://stackoverflow.com/questions/43863522/error-your-push-would-publish-a-private-email-address

4. Tras completar los pasos anteriores, refrescar la ventana de Github.
