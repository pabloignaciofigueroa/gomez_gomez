# Gómez & Gómez — V2 azul marino

Web estática lista para publicar. El documento de entrada es `index.html`, en la raíz del repositorio. No requiere compilación, dependencias de servidor ni variables secretas.

Publicar el contenido de esta raíz en un alojamiento estático (GitHub Pages, Netlify, Vercel o equivalente), conservando las rutas relativas. Para una vista local: `python -m http.server 8783 --bind 127.0.0.1`.

Este repositorio contiene la V2 y sus recursos finales. Las capturas de trabajo intermedias y los originales de la V1 se conservan en el equipo de origen.

## Entrega
- `index.html`, `styles.css`, `script.js`: web HTML/CSS/JS independiente.
- `guia-marca.html`: guía actualizada con azul marino #162B4E protagonista.
- `comparacion.html`: comparación V1/V2 y registro del recorrido.
- `assets/video/`: vídeos locales optimizados, sin audio.
- `analisis/`: comprobaciones, capturas y procedencia.

La V1 está conservada en la carpeta local `gomez-y-gomez`, fuera de este repositorio. No se ha publicado ninguna de las versiones en internet.

## Cambios principales
Navbar azul marino sólido; vídeo de Huicha en portada; presentación de Jorge y mensaje de hogar fusionados en segunda posición; otros proyectos sobre grafito; secuencia de tres vídeos sobre el oficio; transformación de Nercón; contacto azul marino. Huicha no se repite como tarjeta en el portafolio.

Las seis secciones son portada, presentación, obras, oficio, transformación y contacto. Los servicios complementarios se integran en contacto. Anton se utiliza en títulos y CTA, Source Sans 3 en textos y formularios, con fuentes y licencias locales.

## Movimiento y vídeo
GSAP + ScrollTrigger locales: apertura de portada, titular escalonado, salida de título al desplazarse, revelado de retrato, frase en movimiento, apertura de fotografía, secuencia fijada de oficio en escritorio, cotas y comparación de etapas. Microanimaciones en menú, botones y galerías.

Los vídeos se cargan al entrar en pantalla y se pausan al salir o abrir un diálogo. Los controles permiten pausar/reproducir. `prefers-reduced-motion` desactiva animaciones y reproducción automática; los controles manuales siguen disponibles. Las restricciones de autoplay del navegador pueden requerir pulsar reproducir.

Portada: montaje de tomas 4–8 s, 9–15,5 s y 22,5–26,5 s del reel DZdzTd8JWX0, con una corrección global moderada de luminosidad. El recorrido ampliado conserva el tramo 3,8–26,5 s. Todos los vídeos son registros visuales sin audio: no se incluyen entrevistas mudas como si tuvieran sonido.

## Contenido
Número de WhatsApp del perfil: +56 9 9303 6179. El formulario prepara y muestra una consulta; el visitante decide abrir WhatsApp para enviarla. No hay base de datos ni envío automático, y no se enviaron mensajes durante la prueba.

Las fotos de Nercón y Huicha incluyen versiones editoriales generativas realizadas en la V1; sus originales se conservan allí. El logo y el retrato aportados se presentan mediante encuadre CSS. Los estados de obra se expresan según la fuente, sin añadir cifras, precios ni certificaciones.

## Validación
Revisión en Chrome de escritorio, 768, 390 y 320 px; anchura sin desbordamiento horizontal. Reproducción/pausa, cambio de escenas, galería de Notuco con tres imágenes, apertura del recorrido, menú, control de comparación y formulario revisados. Pares de color principales: contraste 6,72:1 hueso/azul marino, 12,99:1 hueso/grafito y 5,10:1 hueso/madera. Código JavaScript comprobado sintácticamente. Capturas y métricas en analisis/.

## Referencias
Silver Pinewood inspeccionado en el navegador y su caso de Vide Infra; ERA y AIR investigados durante el plan. Se toma la jerarquía arquitectónica y la continuidad de recorrido como referencia. El diseño utiliza la identidad de color indicada por el usuario y las obras reales de la empresa.
