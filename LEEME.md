# UECP Nuestros Símbolos - Página web

## Estructura
```
index.html
pdfs/
  horarios/
    1-ano-a/ 1-ano-b/ 2-ano-a/ 2-ano-b/ 3-ano-a/ 4-ano-a/ 5-ano-a/
  cronogramas/
    general/ 1-ano-a/ 1-ano-b/ 2-ano-a/ 2-ano-b/ 3-ano-a/ 4-ano-a/ 5-ano-a/
imagenes/
```

## Cómo agregar un PDF
1. Copia el archivo a su carpeta. Ejemplo: `pdfs/horarios/2-ano-a/horario-de-clases.pdf`
2. Abre `index.html` en Visual Studio Code y busca `const ARCHIVOS`.
3. Escribe el nombre del archivo en la lista de esa sección:
   `"2-ano-a":["horario-de-clases.pdf"]`
   Varios PDF: `"2-ano-a":["horario-de-clases.pdf","actividades.pdf"]`
4. Guarda y recarga la página. El título que se ve sale del nombre del archivo (los guiones pasan a espacios).

Consejo: usa nombres sin acentos ni espacios (`horario-de-clases.pdf`).

## Probar en tu computadora
Instala la extensión **Live Server** en Visual Studio Code, haz clic derecho en `index.html` y elige "Open with Live Server". Abrir el archivo con doble clic también funciona, pero la vista previa del PDF puede variar según el navegador.

## Ejemplos
Los dos PDF `ejemplo-*.pdf` son de prueba. Bórralos y quita su nombre de la lista cuando pongas los reales.
