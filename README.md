# Guide_GIT_Install

Contenido:

- INSTALACIÓN DE GIT EN WINDOWS (10 y 11)
- INSTALACIÓN DE GIT EN LINUX (UBUNTU 20.04.4 LTS y 22.04 LTS)
- CONFIGURACIONES VISUALES EN GITBASH OPCIONALES PERO UTILES (WINDOWS) (OPCIONAL)
- CONFIGURACIONES OBLIGATORIAS SSH ANTES DE INICIAR A TRABAJAR CON GIT Y GITHUB (WINDOWS Y LINUX)
________________________________________

**** INSTALACIÓN DE GIT EN WINDOWS (10 y 11) *****
________________________________________

1 - Primero entramos a la aplicación de GIT desde la pagina oficial https://git-scm.com/

2 - Ya dentro de la página descargamos la última versión estable para nuestro sistema operativo el cual la pagina detecta automaticamente.

![image](https://user-images.githubusercontent.com/54609399/168494367-933c2553-d20f-4ea9-84bc-2ece0c16ded9.png)

Siempre descarga el instalador al dar click en el boton pero en ocaciones nos puede enviar para una pagina dicional y damos click aqui:

![image](https://user-images.githubusercontent.com/54609399/168494407-dca79939-d609-4d0f-bb09-4d83bf60d37c.png)


3 - Una vez descargado procedemos a dar doble click al ejecutable para iniciar la instalación y hacemos los siguientes pasos.

![image](https://user-images.githubusercontent.com/54609399/137605572-8012379e-2220-4f11-9ebd-06ce22e43bff.png)

![image](https://user-images.githubusercontent.com/54609399/137605582-6cf19839-94a5-4c20-b9c3-b9eec196cbb5.png)

4 - Dar check en todas las opciones ya que estas nos permiten añadir GIT en la consola del sistema (CMD), y generan accesos directos en el inicio y en las opciones de click derecho sobre las carpetas, también generan la consola GIT Bash que será una herramienta útil para trabajar GIT. (Es como la consola de comandos pero propia de GIT).

![image](https://user-images.githubusercontent.com/54609399/137605632-db08ce05-4f7c-4ed6-be9a-d14693c498f5.png)

5 - Para los siguientes pasos no se debe modificar ninguna opción, como tampoco dar check en ninguna de las configuraciones que muestra, ya que estas configuraciones adicionales al seleccionarlas pueden generar algunos errores que nos toque solucionar con configuraciones extra, por eso para todas las ventanas de aquí en adelante se dará únicamente click en NEXT.

![image](https://user-images.githubusercontent.com/54609399/137605677-2e9f7120-3376-4471-b8e2-f017aaec30e1.png)

![image](https://user-images.githubusercontent.com/54609399/137605685-de35d755-7576-45d2-a4fc-77bf328fb520.png)

Muy importante seleccionar aqui la opcion main para que genere los repositorios locales sobre esta rama y no la master que ya no se usa

![image](https://user-images.githubusercontent.com/54609399/168494504-1fed177d-b468-4d99-8c0d-3ea79ab69757.png)

![image](https://user-images.githubusercontent.com/54609399/137605713-d574ab9e-a225-4a9d-a605-45b609c50db9.png)

![image](https://user-images.githubusercontent.com/54609399/137605731-f12a2a0d-27c0-4e85-9ce6-8f720f759e25.png)

![image](https://user-images.githubusercontent.com/54609399/137605738-b4beea3a-ae35-44bd-883c-fd29f5268b62.png)

![image](https://user-images.githubusercontent.com/54609399/137605739-bc553f86-4f42-4c65-9fd7-1338987baa1e.png)

![image](https://user-images.githubusercontent.com/54609399/137605743-338ec574-2c76-4043-aa5b-bee801d743fd.png)

![image](https://user-images.githubusercontent.com/54609399/137605750-95daa51c-759e-4031-8986-2aa9b69c1c6d.png)

![image](https://user-images.githubusercontent.com/54609399/168494601-eefc0bd4-4d55-4aa8-aeaf-cd4713b3f721.png)

![image](https://user-images.githubusercontent.com/54609399/137605761-849aee04-e128-47ef-b943-736784f7a9a4.png)

6 - Para finalizar procedemos a dar click en el botón Install.

![image](https://user-images.githubusercontent.com/54609399/137605770-f99f3f1d-fbe5-426d-a2cd-f6efc280bec2.png)

7 - Iniciará el proceso de instalación y configuración de GIT en nuestro equipo, en este paso solo nos toca esperar a que finalice.

![image](https://user-images.githubusercontent.com/54609399/137605783-6d0dbb00-c416-4f20-bf0e-dad4d6a04ec0.png)

8 - Una vez finalizado dejamos solo el check de Launch Git Bash, y damos click en Finish, esto nos abrirá la consola en la cual podemos trabajar GIT.

![image](https://user-images.githubusercontent.com/54609399/137605829-488f8f8b-f58f-4c37-9770-d44aa07c4e70.png)

![image](https://user-images.githubusercontent.com/54609399/137605870-cf5d5b0a-62bc-4dc5-9988-220a59538fc6.png)

9 - Si ejecutamos el comando:
```
git --version
```
Podemos obtener la versión actual instalada en el equipo.

![image](https://user-images.githubusercontent.com/54609399/137605899-1c0a3e1c-d457-485c-a8e9-131fca96be58.png)

10 - También podemos abrir la consola de comandos del sistema operativo y ensayar el comando:
```
git --version
```
Nos dirá la versión del git instalada.

Podemos comprobarlo en nuestra cmd de Windows.

![image](https://user-images.githubusercontent.com/54609399/137605975-a22407c4-139e-42c4-85f2-fd788966f187.png)

![image](https://user-images.githubusercontent.com/54609399/137605989-d3dd14bb-4f96-471a-b940-cb07613c5989.png)

![image](https://user-images.githubusercontent.com/54609399/137606031-bfc19b18-6fe5-4dca-9c0c-8483ab6b5975.png)

Con esto finalizamos el proceso de instalación.

________________________________________

**** INSTALACIÓN DE GIT EN LINUX (UBUNTU 20.04.4 LTS y 22.04 LTS) *****
________________________________________

Para instalar en linux es mas facil que en cualquier otro sistema, recordemos que el creador de linux es el creador de GIT

1 - Abrimos una terminal y ejecutamos el siguiente comando y presionamos ENTER:

```
sudo apt-get install git
```

![image](https://user-images.githubusercontent.com/54609399/167239184-499524ba-15f8-4bb7-8705-e7833cda84ec.png)

2 - Nos pedira nuestra clave de usuario y una confirmación para descargar los paquetes necesarios a la cual daremos que si con una "s" en equipos en español y "y" en equipos en ingles

![image](https://user-images.githubusercontent.com/54609399/163902917-8f0789a8-6c4f-4aa1-a71c-ed51ad12522e.png)

3 - Nos fijamos en la versión que quedo instalada usando el comando:

```
git --version
```

![image](https://user-images.githubusercontent.com/54609399/167239259-d0cf653c-61cc-4b18-a9d7-3a57c70c2bd6.png)

4 - Comparamos con la version oficial que esta en la pagina oficial de GIT

https://git-scm.com/

![image](https://user-images.githubusercontent.com/54609399/167239277-4689287d-900f-4956-a665-2b58f41135af.png)

4 - Como podemos ver nos toca hacer un salto a la siguiente versión estable, para ello solo usamos el siguiente comando:

```
sudo add-apt-repository ppa:git-core/ppa
```

Este comando nos pedira presionar ENTER para confirmar

![image](https://user-images.githubusercontent.com/54609399/167239357-97cd3b1d-9cab-47d4-a0ab-6eacb324b481.png)

5 - Para finalizar solo ejecutamos los siguientes comandos:

Actualizar paquetes con 

```
sudo apt-get update
```
```
sudo apt-get upgrade
```

6 - Verificamos nuecamente la versión
```
git --version
```

Con esto ya tendremos la ultima versión instalada en nuestro equipo

![image](https://user-images.githubusercontent.com/54609399/167239499-138e8724-f51e-4d26-a41a-f3e0235d7b58.png)


________________________________________

**** CONFIGURACIONES VISUALES EN GITBASH OPCIONALES PERO UTILES (WINDOWS) *****
________________________________________

1 - Damos click derecho sobre la consola y click izquierdo sobre options.

![image](https://user-images.githubusercontent.com/54609399/137606195-7a605e93-82e4-472f-a33f-42a27d8a4453.png)

2 - En la primera opción de Looks seleccionamos nivel de transparencia si queremos que nuestra consola de comando tenga un fondo semi transparente, podemos elegir entre off, Low, Medium, high dependiendo nuestro gusto, tener en cuenta que Medium y high hacen que se consuman más recursos del sistema como todo efecto de transparencia en interfaces.

![image](https://user-images.githubusercontent.com/54609399/137606312-64f7ef86-37f7-4af1-99bb-79d432123343.png)

3 - Ahora seleccionamos la opción Text y damos click en el botón Select, este nos llevara a una nueva interfaz, donde seleccionaremos el tamaño de la fuente ya que por defecto la consola de Git es muy pequeña, como paso opcional si gustan pueden cambiar también el tipo de fuente. 

![image](https://user-images.githubusercontent.com/54609399/137606535-7b2be7b3-5925-4ec1-b687-8a874a5a28c7.png)

![image](https://user-images.githubusercontent.com/54609399/137606551-aae4d65c-d435-4df5-83d0-aaf986495c21.png)

4 - Luego de dar aceptar en la ventana anterior, volveremos a la de opciones y damos aplicar luego en save y cerrar esta ventana de options.

![image](https://user-images.githubusercontent.com/54609399/137608162-f4f88796-d188-4468-8a51-5bb0e3a90ba3.png)

5 - Podemos probar cualquier comando GIT y darnos cuenta que ahora es más grande la ventana y el texto, también podemos notar la transparencia.

![image](https://user-images.githubusercontent.com/54609399/137606784-eea506c4-2044-469c-aa36-3653f173b9c5.png)

Con esto terminamos las configuraciones visuales de GIT.

________________________________________

**** CONFIGURACIONES OBLIGATORIAS SSH ANTES DE INICIAR A TRABAJAR CON GIT Y GITHUB (WINDOWS Y LINUX) ****
________________________________________

IMPORTANTE: LAS SIGUIENTES CONFIGURACIONES SOLO SE HACEN LA PRIMERA VEZ QUE SE INSTALA GIT EN EL EQUIPO, UNA VEZ TERMINADAS NO SE DEBEN VOLVER HACER A MENOS QUE SE FORMATEE EL EQUIPO O SE INSTALA GIT EN UN EQUIPO NUEVO.

Para este paso se recomienda tener ya creada una cuenta de GitHub, si no sabes como crear una cuenta puedes ver la siguiente Guía y luego continuar con estos pasos.
https://github.com/sanchezcode/Guide_GitHub/blob/main/README.md

1 - Ahora vamos a realizar unas configuraciones globales en el GIT instalado en el equipo, para eso abrimos la consola de Git Bash en Windows o Terminal de Linux.

![image](https://user-images.githubusercontent.com/54609399/137608213-f4321cf2-c690-4cac-a2d8-d7396b416ea0.png)

![image](https://user-images.githubusercontent.com/54609399/167239802-278e448f-dc57-470d-8ca9-fb0b00fc9eee.png)


2 - Primero tenemos que configurar nombre de usuario y correo de GitHub, para ello usamos los siguientes comandos, debemos asegurarnos que el nombre de usuario cumpla exactamente el que creamos en GitHub respetando mayúsculas, minúsculas en caso tal que las hayamos usado, igualmente el correo debe ser el mismo que se usó para crear la cuenta.

```
git config --global user.name “SuUsuarioDeGitHub”
```
```
git config --global user.email “SuCorreo@correo.com”
```

![image](https://user-images.githubusercontent.com/54609399/137609421-9ab3e6ec-f88c-44a3-9e2d-de9e4f250355.png)

![image](https://user-images.githubusercontent.com/54609399/167239885-9945d6ac-53e3-4d6e-9837-1bdb3645dd83.png)


3 - Verificamos si las configuraciones quedaron bien con el siguiente comando

```
git config --list
```

Este comando nos muestra las configuraciones de GIT en nuestro sistema operativo y deben aparecer las opciones que agregamos de user.name y user.email.

![image](https://user-images.githubusercontent.com/54609399/137609681-f0fc6551-5778-4f75-9b19-5eadbbd70aaa.png)

![image](https://user-images.githubusercontent.com/54609399/167239916-ad7628e7-4fef-40a2-a9bd-4783a6522e6d.png)


NOTA: En caso tal que hayamos escrito mal el user.email o user.name ejemplo: user.nemail o user.names, estas opciones no son válidas:

![image](https://user-images.githubusercontent.com/54609399/137609727-1c57796c-818f-45b3-80b2-5580673d0707.png)

Para solucionar el error de la imagen anterior ejecutamos el siguiente comando que elimina esta opción errada.

```
git config --global --unset-all user.nemail
```

Cambiar "user.nemail" por lo que hayan escrito mal

![image](https://user-images.githubusercontent.com/54609399/137609746-4bae2412-0ea3-49a0-8e96-960afe47eced.png)

Y luego si escribimos los comandos correctos descritos en el punto 2

4 - Como GitHub ya no usa el “master” nos toca cambiar esta opción en GIT local, para cambiarlo usamos el siguiente comando.

```
git config --global init.defaultBranch main
```

![image](https://user-images.githubusercontent.com/54609399/137609760-4ee59c67-5944-41ee-9564-93568d9cbb92.png)

![image](https://user-images.githubusercontent.com/54609399/167239973-bd3a2564-760f-4495-9f7f-76902c5aef92.png)


Verificamos con el comando

```
git config --list
```

Podemos ver que aparece en las opciones

![image](https://user-images.githubusercontent.com/54609399/137609788-ccd67733-f7b9-4294-b2d1-3f44c3918b02.png)

![image](https://user-images.githubusercontent.com/54609399/167239993-5d3110a1-16e0-47a8-9bc6-1b9d1954b08f.png)


5 - Ahora necesitamos generar una clave SSH (Secure Shell) para GitHub, esto hará que GIT local y GITHUB se comuniquen por medio de una llave de conexión, escribimos el siguiente comando.

```
ssh-keygen
```

Nos va pedir unas confirmaciones para las cuales damos ENTER tres veces, la primera es la ruta donde necesita crear una carpeta ssh para guardar las key, la segunda es generar una frase de seguridad la cual si escribimos algo es posible que luego se nos olvide y no podamos acceder a las key, por ende las dejaremos vacias, la tercera opcion es confirmación de esa clave que generamos para acceder a las key, como en este caso no generamos entonces damos enter también sin escribir nada.

En conclusión, después de escribir el comando ssh-keygen y presionar enter, nos pedirá las opciones mencionadas anteriormente y solo tenemos que dar ENTER tres veces.

![image](https://user-images.githubusercontent.com/54609399/137609967-07d20717-839c-428c-bfbe-2475088ee49b.png)

![image](https://user-images.githubusercontent.com/54609399/167240020-f1e7f1ea-effb-46e0-b91d-c583275b5565.png)


6 - Ahora podemos mostrar nuestra llave aplicando el siguiente comando y presionando ENTER:

```
cat ~/.ssh/id_rsa.pub
```

![image](https://user-images.githubusercontent.com/54609399/137610010-b6f0efe4-225e-4ee5-be27-5df7ba9402f9.png)

![image](https://user-images.githubusercontent.com/54609399/167240163-16f51296-6f64-4866-9037-a99dce25b514.png)


Luego de generarla la copiamos sin espacios vacíos, ya que vamos a tener que pegarla en GITHUB.

![image](https://user-images.githubusercontent.com/54609399/137610051-53ca2cbc-c085-4ba3-b528-e4c01061241d.png)

![image](https://user-images.githubusercontent.com/54609399/167240187-f6c35378-61a5-4e2f-a5ec-8297c69bd723.png)


7 - Ahora vamos a pegar la clave en GITHUB pero primero tenemos que ir a nuestro usuario/perfil y damos click  a settings.

![image](https://user-images.githubusercontent.com/54609399/137610096-6a0fa50d-4dc8-40d0-bd75-2767fd45124f.png)

8 - Seleccionamos la opción SSH and GPG Keys.

![image](https://user-images.githubusercontent.com/54609399/137610120-eb25000f-2edf-46f5-8ed8-9cf9760c4801.png)

9 - Damos click en New SSH Key.

![image](https://user-images.githubusercontent.com/54609399/137610169-2cc70e34-4969-4fa8-bfb1-5570a95455f3.png)

10 - Creamos un nombre (Title ) para la clave, puede ser cualquier nombre que identifique el equipo que vamos a utilizar, y pegamos la clave que generamos por consola.

![image](https://user-images.githubusercontent.com/54609399/137610232-8a5e356a-4c84-435f-877e-1b322348dac5.png)

![image](https://user-images.githubusercontent.com/54609399/137610273-4ad4ca6c-3bda-431c-ba25-eab8117dd8ae.png)

Para finalizar damos click en el botón Add SSH Key. (Puede que a veces nos pida confirmar la contraseña de GitHub)

Nos devuelve a la pantalla de configuración y nos muestra nuestra key creada, también podemos crear las Key que queramos.

![image](https://user-images.githubusercontent.com/54609399/137610362-de3ee25e-664a-43a1-ba32-87a1d06f9d2f.png)

Con esto ya tenemos la llave generada en GIT y enlazada con GITHUB.
