# Configurando el proyecto

Tener instalado ```NodeJS```.

No instalaremos TypeScript de manera global, sino solo en el proyecto.ya que se suele trabajar a nivel de proyecto.

1.Crear una carpeta para el proyecto "nombre que desees"

```shell
  mkdir ts-project
```
Revisar si se tiene instalado typescript

```shell
  cd tsc --version
```
2. Abre el editor de código desde la carpeta del proyecto. Si estás utilizando Visual Studio Code, puedes hacerlo desde la terminal con el siguiente comando:

```shell
code .
```

2. Crear los siguientes archivos

* primer paso ingrese al siguiente enlace: [gitignore.com](https://www.toptal.com/developers/gitignore), seleccionar mac, windows , linux  y node.

Secopia la creacion y se pega en un archivo ```.gitignore```

* Crear un archivo .editorconfig 
es para que todos tengamos la misma configuraición. Aquí copia y pega lo siguiente:

```editorconfig
# Editor configuration, see https://editorconfig.org
root = true

[*]
charset = utf-8
indent_style = space
indent_size = 2
insert_final_newline = true
trim_trailing_whitespace = true

[*.ts]
quote_type = single

[*.md]
max_line_length = off
trim_trailing_whitespace = false
```
Para que funcione .editorconfig instale la extension desde Visual Studio Code

3. Crear una carpeta de nombre ```src``` en tu proyecto

4. Crear el package.json  desde la terminal y dentro de la ruta del proyecto

<!-- Dependencias package.json -->
```shell
npm init -y
```
5. Finalmente instale TypeScript. Desde la terminal y dentro de la ruta del proyecto, ejecuta.


```shell
npm install typescript --save-dev
```
Para verificar la versión instalada:

```shell
npx tsc --version
```
