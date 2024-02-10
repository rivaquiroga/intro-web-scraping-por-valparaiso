# Introducción al web scraping con Python

En este taller aprenderemos a implementar la técnica de extracción de datos conocida como web scraping sobre sitios web estáticos usando la librería Beautiful Soup.

## Preparación 

Para realizar las actividades planificadas necesitarás las librerías `request`, `beautifulsoup4`, `lxml` y `pandas`. Se pueden instalar desde [PyPI](https://pypi.org/) con `pip`.  Al inicio de la sesión mostraremos cómo hacerlo, pero dejaremos el código acá como respaldo. 

```
pip install beautifulsoup4
pip install requests
pip install pandas
pip install lxml
```

Si prefieres trabajar en Google Colab, no olvides agregar un signo de exclamación al inicio de cada línea para su instalación, es decir:

```
!pip install beautifulsoup4
!pip install requests
!pip install pandas
!pip install lxml
```
(Esto le indica a Google Colab que ese no es código de Python, sino código que tiene que ejecutarse en la Terminal.)

Si trabajas en Visual Studio Code o en otro IDE, será necesario que crees un entorno virtual. En Google Colab no es necesario, ya que cada _notebook_ es ya un entorno virtual.
Al inicio de la sesión mostraremos cómo hacerlo. De todos modos, dejaremos un respaldo con [las indicaciones en este documento](https://github.com/rivaquiroga/datapalooza2024-webscraping/blob/main/crear-entorno-virtual.md).

## Enlaces ejemplos

A lo largo de la sesión revisaremos algunos sitios web a modo de ejemplo o para discutir algunas ideas. 

:link: [Sitio web estático](https://datascience.uc.cl/que-es-ciencia-de-datos)

:link: [Sitio web dinámico](https://www.camara.cl/transparencia/asesoriasexternasgral.aspx)

:link: [Condiciones de uso](https://www.amazon.com/-/es/gp/help/customer/display.html?nodeId=508088&ref_=footer_cou) 

:link: [Licenciamiento y uso del contenido 1](http://programminghistorian.org/es/)

:link: [Licenciamiento y uso del contenido 2](https://prensa.presidencia.cl/)

:link: [robots.txt 1](https://es.wikipedia.org/robots.txt)

:link: [robots.txt 2](https://www.memoriachilena.gob.cl/robots.txt)

## Actividades




## Atajos de teclado útiles

Los siguientes atajos de teclado serán útiles al explorar las páginas web que _escrapearemos_.

| Acción | Windows / Linux | Mac |
|---|---|---|
| Ver el código fuente de una página | ctrl +  u | command + u|
| Abrir el panel de desarrollo | F12<br/>ctrl + shift + i | F12<br/>option + command +i |
| Abrir el panel de desarrollo con la opción de selección activada | ctrl + shift + c | option + command + c |
