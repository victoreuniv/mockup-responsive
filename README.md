# Fluido — laboratorio de diseño responsivo

Pequeña web didáctica en español para mostrar cómo se adapta una interfaz a móvil, tablet y escritorio. No requiere dependencias ni proceso de compilación.

## Conceptos que se pueden identificar

- Rejillas fluidas con CSS Grid y unidades `fr`.
- Unidades relativas (`rem`, `%`, `min()`, `clamp()`) y contenedores flexibles.
- Media queries y tres rangos visibles: móvil (hasta 639 px), tablet (640–959 px) y escritorio (960 px en adelante).
- Menú que se simplifica, tarjetas que cambian de columnas y contenido que se reorganiza.
- Indicador en vivo del ancho de la ventana.
- Accesibilidad básica: idioma, foco visible, enlace para saltar al contenido y preferencia de movimiento reducido.

## Publicar con GitHub Pages

1. Abre **Settings → Pages** en el repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/(root)`; pulsa **Save**.
4. Espera a que termine el despliegue. La URL aparecerá en esa misma sección de Pages.

La página de entrada es `index.html`; `styles.css` contiene los estilos y breakpoints.
