# FORZA — Mi Progreso

App web instalable para registrar peso (kg), repeticiones por serie, historial y gráficas en una rutina PPL + Upper/Lower de lunes a viernes.

## Publicar en Vercel

1. En [Vercel](https://vercel.com/new), importa el repositorio `svchost-64/svchost-64`.
2. En **Root Directory**, pulsa Edit y selecciona **forza-app**.
3. Framework Preset: **Other**. No build command, no environment variables.
4. Pulsa **Deploy** y abre la URL HTTPS generada.
5. Desde Safari en iPhone: compartir → **Añadir a pantalla de inicio**.

## Privacidad

Los registros se guardan **solo en el navegador** mediante localStorage. No existe cuenta ni sincronización en la nube. No son visibles en GitHub ni en Vercel. Exporta respaldos JSON periódicamente desde Perfil y evita borrar datos de Safari sin tener una copia.

Si usas otra URL, navegador, o dispositivo, los datos previos no se trasladan automáticamente.

## Desarrollo local

Sirve esta carpeta con un servidor HTTP local (por ejemplo `python -m http.server 8000`) para comprobar instalación y service worker. `index.html` puede abrirse como archivo para una prueba rápida, pero no admite service worker desde `file://`.
