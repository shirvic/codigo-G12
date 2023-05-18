# Primer día con Git y Gitbush

* Para poder ver la version de git que ejecutamos en nuestro temrinal:

```Bash

git --version
git--v

````

* Para configurar el correo y nombre (sólo la primera vez en mi maquina)

```

git config --global user.email "micorreo@gmail.com"
git config --global user.name "minombre"

```

* Para ver la configuracióin de git:

```bash
git config --list
```

* Para inicializar nuestro repositorio en git:

```bash
git init
```

* Para ver el estado de nuestro cambio:

```bash
git status
```

* Para preparar nuestros archivos para la zona de stage (prepararlos para commit)

```bash
git add .
git add nombreDelArchivo.extensión
```

* Crear el registro de los cambios realizados

```bash
git commit -m "comentario corto y conciso"
```

* Para ver una linea de tiempo de los cambios que hemos realizado:

```bash
git log
```

* Para poder ver los detalles de un commit especifico que usamos:

```bash
git show id-de-commit
```
