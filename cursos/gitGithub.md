# Comandos Git
### Comandos de Navegación y Gestión de la Consola
`ls`

Ver los archivos de la carpeta en donde nos encontramos.

`cd`

Moverse entre archivos (con el TAB se autocompleta el nombre del archivo).

`clear`

Limpiar la consola.

`code .`

Abrir la carpeta actual en Visual Studio Code.

`git init`

Iniciar un repositorio en una carpeta vacía.

### Gestión de Ramas
`git branch`

Muestra las ramas que tenemos.

`git checkout -b nombre`

Crea una nueva rama y se cambia a ella.

`git switch main`

Moverse entre ramas.

`git merge ramaSecundaria`

Fusionar una rama secundaria con la rama main.

### Visualización del Estado y Historial

`git status`

Verifica el estado de los archivos/carpetas.

`git log`

Visualizar el historial de commits (cambios).

`git log --oneline`

Igual que git log pero resumido.

`git diff`

Visualizar cambios entre el último commit y los cambios actuales.

### Trabajando con Cambios

`git add .`

Añadir todos los archivos modificados al área de preparación.

`git commit -m "mensaje"`

Crear un commit con un mensaje descriptivo.

`git pull`

Verifica si está todo actualizado.

`git pull origin main`

Utilizar cuando tengas 2 o más ramas que se están chocando entre sí (usar solo en casos específicos).

`git push origin main`

Enviar los cambios al repositorio remoto en la rama main.

`git restore --source codigo nombrearchivo.html`

Volver a una versión antigua de un archivo específico.

### Otros Comandos

`git pull origin main`

Utilizar cuando tengas 2 o más ramas que se están chocando entre sí (usar solo en casos específicos).