# UNTREF Website

Este repositorio contiene el código fuente del sitio web de **UntrefSchool**, un instituto de educación. El proyecto incluye una página principal y estilos personalizados.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

```
[`index.html`](index.html )
assets/
    backgroundimage.webp
    favicon.png
    logo_untref.webp
    porque_elegirnos.webp
    quienes_somos.webp
css/
    [`css/style.css`](css/style.css )
    fonts/
        [`css/fonts/fonts.css`](css/fonts/fonts.css )
    modules/
        [`css/modules/footer.css`](css/modules/footer.css )
        [`css/modules/formulario_contacto.css`](css/modules/formulario_contacto.css )
        [`css/modules/header.css`](css/modules/header.css )
        [`css/modules/nav.css`](css/modules/nav.css )
        [`css/modules/scrollbar.css`](css/modules/scrollbar.css )
        [`css/modules/section.css`](css/modules/section.css )
```

### Archivos Principales

#### `index.html`
La página principal del sitio web. Contiene las siguientes secciones:
- **¿Quiénes somos?**
- **¿Por qué elegirnos?**
- **Propuesta educativa**
- **Últimas noticias**
- **Contacto**

Incluye un formulario de contacto funcional que utiliza [FormSubmit](https://formsubmit.co/) para enviar mensajes.

#### `css/style.css`
Archivo principal de estilos que importa módulos específicos para cada sección del sitio:
- `formulario_contacto.css`: Estilos del formulario de contacto.
- `footer.css`: Estilos del pie de página.
- `header.css`: Estilos del encabezado.
- `nav.css`: Estilos de la barra de navegación.
- `section.css`: Estilos de las secciones principales.
- `scrollbar.css`: Personalización de la barra de desplazamiento.

#### `assets/`
Contiene imágenes utilizadas en el sitio, como el logotipo, imágenes de fondo y fotos de las secciones.

### Fuentes
El proyecto utiliza las siguientes fuentes:
- **Poppins**: Fuente principal para el contenido.
- **Belanosima**: Fuente secundaria para encabezados.

Las fuentes son importadas desde Google Fonts en el archivo [`css/fonts/font-poppins.css`](css/fonts/font-poppins.css).

## Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tizianoluziramos/PROYECTO-INTEGRADOR-WEB-UNTREFSCHOOL.git
   ```
2. Abre el archivo `index.html` en tu navegador para ver la página principal.

## Créditos

- **Autor**: Tiziano Tomas Luzi Ramos
- **Contacto**: UntrefSchool@gmail.com

## Licencia

Este proyecto está bajo una licencia abierta. Puedes usarlo y modificarlo libremente.