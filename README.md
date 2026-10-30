# Proyecto-MAG-SCSS-CSS-TAREA
Tarea de Conquer Blocks, SCSS-CSS, terminada con mucho exito!!

Mini-sitio de **dos vistas** (Home y Location) para la galería ficticia **Modern Art Gallery**, maquetado **mobile first** con HTML semántico y SASS, siguiendo fielmente el PDF de la *Tarea entregable 3 de CSS* (versiones mobile, tablet y desktop).

## Vistas

| Vista | Archivo | Contenido |
| --- | --- | --- |
| Home | `index.html` | Hero, galería "Your day at the gallery", bloque "Come & be inspired" y footer oscuro |
| Location | `location.html` | Mapa de Newport con pin, botón "Back to home", dirección y footer dorado |

## Requisitos cubiertos

- Boilerplate propio, organizado por carpetas
- SASS con parciales (`abstracts`, `base`, `layout`, `components`, `pages`)
- Iconos en SVG (flechas y redes sociales)
- HTML semántico: `header`, `main`, `section`, `article`, `figure`, `address`, `footer`
- Fidelidad al diseño del PDF en mobile, tablet y desktop
- Mapa responsive con `<picture>` (tres imágenes según el ancho) y pin superpuesto con CSS
- Estados `hover` y `focus-visible` en botones, enlaces y redes sociales
- Media queries mobile first: `768px` (tablet) y `1200px` (desktop)
- Imágenes con `alt` descriptivo, un único `h1` por página

## Stack

- HTML5
- SASS / CSS3 (Grid + Flexbox)
- Google Fonts: [Big Shoulders Display](https://fonts.google.com/specimen/Big+Shoulders+Display) (900) y [Outfit](https://fonts.google.com/specimen/Outfit) (300)

## Sistema de diseño

| Color | Valor |
| --- | --- |
| Gold | `#D5966C` |
| Almost black | `#151515` |
| Dark grey | `#444444` |
| White | `#FFFFFF` |

| Estilo | Fuente | Tamaño / interlineado |
| --- | --- | --- |
| Heading XL | Big Shoulders Display Black | 96 / 88 px |
| Heading L | Big Shoulders Display Black | 70 / 70 px |
| Heading M | Big Shoulders Display Black | 60 / 50 px |
| Heading S | Big Shoulders Display Black | 36 / 36 px |
| Body M | Outfit Light | 22 / 32 px |
| Body S | Outfit Light | 18 / 28 px |

## Estructura

```text
.
├── index.html
├── location.html
├── package.json
├── css/
│   └── styles.css        # CSS compilado
├── scss/
│   ├── main.scss
│   ├── abstracts/        # variables y mixins
│   ├── base/             # reset
│   ├── components/       # botones
│   ├── layout/           # hero, gallery, footer
│   └── pages/            # location (mapa y dirección)
├── assets/
│   ├── icons/            # SVG
│   └── images/
├── LICENSE
└── README.md
```

## Uso en local

1. Abre `index.html` en el navegador (o sirve la carpeta con `npx serve .`).
2. Si quieres editar estilos, instala y compila SASS:

   ```bash
   npm install
   npm run sass     # modo watch
   npm run build    # compilación única
   ```

## Licencia

MIT — ver [LICENSE](./LICENSE).
