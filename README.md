# Rutina de las mañanas

Guía interactiva en español: 3 ejercicios con una mancuerna, letra grande, botón para escuchar y fotos de forma correcta / incorrecta.

**Sitio (cuando Pages esté activo):** https://radiolactive.github.io/rutina-mananas/

**Repo:** https://github.com/radiolactive/rutina-mananas

## Sí: ella ve el cambio en la misma URL

Cuando Pages ya está encendido, cada vez que se actualiza `main` (texto o fotos) el sitio se republica solo. No hay que mandarle un archivo nuevo. A veces el teléfono guarda caché: cierra la pestaña y vuelve a abrir el link.

## Activar Pages (solo tú, una vez)

GitHub no deja que el robot lo encienda. Tienes que hacerlo en el navegador:

1. Abre https://github.com/radiolactive/rutina-mananas/settings/pages
2. En **Build and deployment** → **Source** elige **GitHub Actions**
3. Guarda. En 1–2 minutos el workflow `Deploy GitHub Pages` deja de fallar y el link de arriba funciona.

## Fotos

Ya están en el repo la portada (`85OBt`) y cómo sujetar la mancuerna (`LM8Sn`). El resto vive en la carpeta `img/` (archivos `.b64`). Si alguna no carga, sube el zip `fotos_para_github.zip` así:

1. Repo → **Add file** → **Upload files**
2. Arrastra la carpeta `img/` (y si quieres `p/` e `index.html`)
3. Commit to `main`

## Cómo abrirla en el celular

1. Entra a https://radiolactive.github.io/rutina-mananas/ (cuando Pages ya esté verde)
2. Toca **A+** si la letra se ve chica
3. Toca **Escuchar esta pantalla**
4. En Safari/Chrome: “Agregar a pantalla de inicio”

Si Pages todavía no está, ábrele el archivo `Rutina_mananas.html`: lleva las 13 fotos adentro y funciona sin internet.
