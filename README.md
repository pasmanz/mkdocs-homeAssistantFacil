# Web Wiki canal telegram Home Assistant Fácil

Aquí está la web de ayuda para el canal de telegram Home Assistant Fácil https://t.me/DomoticaFacilHomeAssistant, la dirección de la web es esta: https://modest-carson-357eb7.netlify.app/

## Tecnología usada
La web es estática y está realizada con [MkDocs](https://www.mkdocs.org/) con el tema [Material](https://squidfunk.github.io/mkdocs-material/), está integrada con Netlify, de tal manera que todo cambio que se produce en este 
repositorio se reflejará en la web.

## Si no encuentras un contenido o la información es incorrecta
Si no encuentras un tema, es incorrecto y te gustaría que apareciera en la wiki, nos lo puedes comunicar vía Telegram

## Como desplegar el proyecto en local

1. Clona tu repositorio en local:

``` 
git clone https://github.com/pasmanz/mkdocs-homeAssistantFacil.git
```

2. Instala Python, Pip y Mkdocs en tu equipo, [guía](https://www.mkdocs.org/user-guide/installation/#installing-python)
3. Instala el tema Material, [guía](https://squidfunk.github.io/mkdocs-material/getting-started/)
4. Construye el proyecto, en el directorio donde te has descargado el proyecto, ejecuta:
``` 
mkdocs build
```
5. Arranca el proyecto para poder verlo en local
``` 
mkdocs serve
```
6. Accede desde un navegador a la siguiente URL: http://localhost:8000/

Recuerda que si usas windows, quizás tengas que poner antes el comando `python -m`
