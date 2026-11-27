# Recursos de «Reels con Claude»

Recursos comunes para editar reels con las skills de «Reels con Claude»: stickers, catálogo de stickers y música de fondo.
Este repo (github.com/tumblster/recursos-aceleradora) **no** contiene las skills: se comparten aparte, como archivo.

## Qué hay
| Carpeta | Contenido |
|---|---|
| `Stickers/imagenes-memes/` | Imágenes que acompañan una frase, elegidas por la emoción de lo que se dice. |
| `Stickers/stickers-apoyo/` | Adornos para las esquinas: estrellas, brillos, sobre, chinche… |
| `Stickers/catalogo.md` | Qué se ve en cada sticker y cuándo usarlo. Claude lo lee para elegir. |
| `Música/` | La música de fondo de los reels. |

## Cómo se instala
No hace falta cuenta de GitHub. En Claude, con las skills ya instaladas, basta con pedir: «descarga los recursos de mis reels».
Claude ejecuta `descargar_recursos.py`, que baja este repo como zip y copia `Stickers/` y `Música/` en `Documentos/Reels con Claude`, sin pisar lo que ya haya.
