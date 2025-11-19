# Hoja de comprobación — Práctica 9 (Usabilidad y Accesibilidad)

**Nombre:**  
**URL del sitio principal:**  
**URL del blog publicado:**  

## Requisitos de la práctica
- [ ] Blog creado en WordPress.com (plan gratuito aceptable).
- [ ] Blog con al menos 3 entradas (posts) relacionadas con la temática.
- [ ] Entre las entradas: imágenes con `alt`, tablas, vídeos con subtítulos, buen contraste, subtítulos si procede.
- [ ] Blog publicado (no en estado "Próximamente" o privado).

## Accesibilidad aplicada (por página/elemento)
| Característica | WCAG 2.x | Nivel | Dónde se aplica | Evidencia |
|---|---:|---:|---|---|
| Idioma del documento | 3.1.1 | A | blog_iframe.html (lang="es") | Archivo principal del proyecto |
| Título del iframe | H64 | A | blog_iframe.html (atributo title) | blog_iframe.html |
| Enlace alternativo | 2.4.4 | A | blog_iframe.html (enlace 'Abrir el blog') | blog_iframe.html |
| Contraste de color | 1.4.3 | AA | CSS del tema / entradas | Medir con herramienta de contraste |
| Imágenes con texto alternativo | 1.1.1 | A | Entradas del blog | Revisar cada imagen |
| Subtítulos en vídeos | 1.2.2 | A | Vídeos insertados en entradas | Archivo .vtt incluido en proyecto |
| Estructura de encabezados | 2.4.6 | AA | Tema del blog / entradas | Revisar jerarquía H1..H6 |
| Navegación por teclado | 2.1.1 | A | Menú y bloques del blog | Probar sin ratón |
| Formularios etiquetados | 3.3.2 | A | Si hay formularios | Revisar etiquetas <label> |

## Pasos realizados (descripción breve)
1. Creado blog en WordPress.com y publicado en la URL: ...
2. Generadas 3 entradas: (títulos) ...
3. Insertadas imágenes con `alt`, vídeos con subtítulos .vtt, tablas accesibles.
4. Añadido visor del blog embebido mediante `iframe` en `P9/blog_iframe.html`. Se aplicó CSS responsive en `css/iframe.css`.
5. Comprobado que, si el servidor bloquea el iframe (X-Frame-Options), se ofrece enlace alternativo.

## Limitaciones / características que no se pudieron añadir con la interfaz de WordPress
- (Describe aquí cualquier característica que solo se podría hacer editando HTML/CSS y que WordPress no permita sin instalar plugins o editar temas.)

## Firma
Firma: ______________________   Fecha: __________
