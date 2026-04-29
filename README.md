# 1bite.studio

Sitio estático de 1bite Studio. Originalmente WordPress + Elementor, exportado a HTML estático para deployment en GitHub Pages.

## Estructura

- `index.html` — Home
- `1bitecircle/` — 1bite Circle
- `nuestros-proyectos/` — Portfolio
- `hagamos-realidad-tus-ideas/` — CTA / formulario
- `contact/` — Contacto
- `wp-content/` — Assets (imágenes, CSS, JS de Elementor)
- `wp-includes/` — Librerías base (jQuery, etc.)

## Deploy

GitHub Pages bajo dominio `1bite.studio` (apex). El subdominio `app.1bite.studio` queda libre para la app 1bite.

## Local dev

```
python3 -m http.server 4880
# → http://localhost:4880/
```

## Pendiente

- Reconstruir formularios de contacto (actualmente apuntan a `mailto:` temporal)
