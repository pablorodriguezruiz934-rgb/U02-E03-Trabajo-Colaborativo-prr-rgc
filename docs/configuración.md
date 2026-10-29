Ejemplo de modificación de archivo

# Guía de configuración

## Configuración de Git

Para configurar el nombre del autor de los commits:

```bash
git config --global user.name "Nombre del usuario"
```

Para configurar el correo electrónico:

```bash
git config --global user.email "correoejemplo@gmail.com"
```

Para consultar la configuración:

```bash
git config --list
```

## Repositorio remoto

Para consultar el repositorio remoto configurado:

```bash
git remote -v
```

El repositorio remoto debe apuntar al proyecto correcto de GitHub.

## Configuración de la aplicación

La aplicación debe configurarse según los componentes que realmente tenga implementados.

Si actualmente solo contiene archivos HTML de prueba, no es necesario inventar una configuración de base de datos o servidor.
