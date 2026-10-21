# Test de Innovación Docente — entorno de pruebas

Aplicación web estática para practicar con el banco de preguntas de la asignatura **Innovación Docente e Iniciación a la Investigación Educativa de Matemáticas (MAES)**.

## Estructura
- `index.html`: aplicación web autocontenida.
- `.github/workflows/pages.yml`: publicación automática de la rama `develop` en GitHub Pages.
- `.nojekyll`: desactiva el procesamiento Jekyll.

## Ramas
- `develop`: entorno de pruebas; sus cambios se publican automáticamente en GitHub Pages.
- `main`: rama estable, no fusionar cambios hasta validar expresamente la versión de pruebas.

## Activación inicial
1. En **Settings → Pages**, elige **GitHub Actions** como fuente de publicación.
2. Sube el archivo de la aplicación como `index.html` y el workflow `.github/workflows/pages.yml`.
3. Los cambios en `develop` activarán la publicación. Consulta **Actions** para ver el resultado y la URL.

## Privacidad
Este repositorio es público. Todo el código y las preguntas incluidos en la aplicación serán visibles públicamente. No incluir el Excel original ni documentos internos de trabajo.

## Estado
Entorno de pruebas inicial. Verificar el funcionamiento en navegador tras el primer despliegue.
