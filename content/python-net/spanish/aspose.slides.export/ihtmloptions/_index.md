---
title: IHtmlOptions class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions clase

Representa una opción de exportación HTML.

El tipo IHtmlOptions expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`html_formatter`](/slides/python-net/es/aspose.slides.export/ihtmloptions/html_formatter/) | Devuelve o establece la plantilla HTML.<br/>            Lectura/escritura [`IHtmlFormatter`](/slides/python-net/es/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/es/aspose.slides.export/ihtmloptions/slide_image_format/) | Devuelve o establece las opciones de formato de imagen de diapositiva.<br/>            Lectura/escritura [`ISlideImageFormat`](/slides/python-net/es/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/ihtmloptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/ihtmloptions/jpeg_quality/) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.<br/>            Lectura/escritura **int**. |
| [`pictures_compression`](/slides/python-net/es/aspose.slides.export/ihtmloptions/pictures_compression/) | Representa el nivel de compresión de las imágenes<br/>            Lectura/escritura [`IHtmlOptions.pictures_compression`](/slides/python-net/es/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/es/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán, si es false, se serializarán en el documento (lo que puede posible llevar a un<br/>            archivo más grande)<br/>            Lectura/escritura **bool**. |
| [`svg_responsive_layout`](/slides/python-net/es/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | True para excluir los atributos de ancho y alto del contenedor SVG - lo que hará que el diseño sea responsivo. False - en caso contrario.<br/>            Lectura/escritura **bool**. |
| [`disable_font_ligatures`](/slides/python-net/es/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras.<br/>            Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en `false`. |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/ihtmloptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/ihtmloptions/ink_options/) | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)