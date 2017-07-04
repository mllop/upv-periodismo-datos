# upv-periodismo-datos
Curso periodismo de datos. UPV, julio de 2017
## Día 1
Ricard Martínez
Adolflow
### Antecedentes del periodismo de datos
Philip Meyer (padre del periodismo de precisión, pero no fue el único que hizo cosas)
Adrian Holovaty
Aron Pilhofer
Simon Rogers
### Necesitamos:
**Navegador**: Firefox y/o Chrome
**Editor de texto**: Emacs, Notepad ++, Sublime
**Consola**: CYGWIN 
### Más info sobre GitHub:
Información [documentada] por Adolflow (https://github.com/flowsta/markdown "Title")
> Esto es un bloque de cita
> Empieza aquí
> Y sigue por aquí
```
# /etc/nsswitch.conf
#
#    This file is read once by the first process in a Cygwin process tree.
#    To pick up changes, restart all Cygwin processes.  For a description
#    see https://cygwin.com/cygwin-ug-net/ntsec.html#ntsec-mapping-nsswitch
#
# Defaults:
# passwd:   files db
# group:    files db
# db_enum:  cache builtin
# db_home:  /home/%U
# db_shell: /bin/bash
# db_gecos: <empty>
 
# Estoy personalizando la variable de entorno de la home de cygwin para que se corresponda con la de mi usuario de Windows
 
 db_home:  /%H
```
