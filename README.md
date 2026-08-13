# 01-Proyecto-Django
**Autor:** Pablo Pizarro

A continuación se detallan los comandos utilizados para la configuración inicial y el control de versiones del proyecto:

### 1. Configuración de Usuario en Git

Muestra la configuración global actual de Git en tu equipo:
```bash
git config --global --list
```

Establece el nombre de usuario que quedará registrado en los commits:
```bash
git config --global user.name ppablo2802
```

Establece el correo electrónico que se asociará a tus commits:
```bash
git config --global user.email pablopizarro662@gmail.com
```

### 2. Guardado y Subida de Cambios (Flujo de Trabajo)

Agrega todos los archivos nuevos o modificados en el directorio actual para guardarlos:
```bash
git add .
```

Confirma los cambios guardados creando un commit, adjuntando un mensaje que describe lo que se modificó:
```bash
git commit -m "Readme modificado, nombre agregado"
```

Sube (empuja) los commits locales a la rama `main` del repositorio remoto:
```bash
git push origin main
```