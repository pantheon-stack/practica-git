# Practica Git
Repositorio para practicar Git

## Cómo practicar

Los cambios en la rama main esta protegido para que unicamente los cambios se realicen por medio de pull request (PR)

Ante cualquier duda se puede consultar el [libro de git gratuito](https://git-scm.com/book/), acá lo utilizaremos para guiarnos con varios ejemplos prácticos

## Prepara tu entorno

1. Descarga e instala Git en tu equipo desde la [página oficial](https://git-scm.com/download)
2. Busca *Git Bash* en tu equipo y abrelo (si inicia sin problemas ya esta instalado)
3. (Opcional) Agrega o verifica que Git este en las variables de entorno (En Windows por defecto es C:\Program Files\Git\cmd para OS x64)
4. (Opcional) Abre la consola (cmd, powershell, bash o shell) desde tu equipo
5. (Opcional) Ejecuta la siguiente linea
```
  git --version
```
Deberia mostrar algo como
```
  git version x.xx
```

## Clonando un repositorio

1. Abre la consola de git (*Git Bash*)
2. Dirigete al lugar donde quieras agregar el proyecto (En mi caso D:/projects)
```
  cd D:/projects
```
4. Escribe, si tienes configurado SSH,
```
  git clone git@github.com:pantheon-stack/practica-git.git
```
  Si no,
```
  git clone https://github.com/pantheon-stack/practica-git.git
```
4. Esto clonará el projecto usando como nombre de carpeta el nombre del proyecto *practica-git*
5. Listo! Ya puedes comenzar a trabajar


## Qué puedo hacer

1. Empieza creando una nueva rama<sup>1</sup>
```
  git checkout -b usuario_nombre_de_rama
```
3. Crea un archivo de texto y escribe "Hello World"
4. Abre la consola de git en el directorio donde clonaste el proyecto (En mi caso D:/projects/practica-git)

<sup>1</sup> Al crear una nueva rama, es muy importante el nombre que le ponemos a esta, puesto que representa la funcionalidad en la que estamos trabajando, siempre se definen esctructuras para los nombres de las ramas y, generalmente, se eliminan una vez que se terminan.

#### Este es un proyecto con fines educativos de git, utilizando como referencia la documentación existente para fomentar el uso de esta.
#### Este readme es temporal mientras se trabaja en la Wiki
