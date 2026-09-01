# Equipos que se potencian

Página web de **Santiago Fernández** — ingeniero industrial y coach organizacional.
Acompañamiento de equipos en industrias y PyMEs.

## Qué hay acá

Un sitio estático de un solo archivo. Sin build, sin dependencias, sin framework.

```
index.html      la página completa (HTML + CSS en línea)
netlify.toml    configuración de deploy y cabeceras
robots.txt      indexación abierta
```

Las únicas cargas externas son las tipografías (Archivo y Newsreader) desde Google Fonts.

## Deploy en Netlify

1. En Netlify: **Add new site → Import an existing project → GitHub**.
2. Elegir este repositorio.
3. Netlify lee `netlify.toml`, así que los campos quedan así (no hace falta tocar nada):
   - Build command: *vacío*
   - Publish directory: `.`
4. **Deploy**.

Cada push a `main` vuelve a deployar solo.

### Dominio propio

En **Site configuration → Domain management → Add a domain**, y seguir las
instrucciones de DNS que da Netlify. El certificado HTTPS lo emite Netlify
automáticamente (Let's Encrypt).

## Editar la página

Todo el contenido y los estilos están en `index.html`. Se edita ese archivo,
se hace commit y push, y Netlify publica el cambio en menos de un minuto.

Para ver el resultado antes de publicar, abrir `index.html` en el navegador:
no necesita servidor.

## Contacto

- Mail: santifernan@gmail.com
- WhatsApp: +54 9 11 6798-7710
- LinkedIn: [linkedin.com/in/santifernan79](https://www.linkedin.com/in/santifernan79/)
