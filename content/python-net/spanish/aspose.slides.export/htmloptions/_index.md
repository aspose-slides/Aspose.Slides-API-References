---
title: HtmlOptions class
second_title: Aspose.Slides para Python mediante la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.export/htmloptions/
---
## HtmlOptions clase

Representa opciones de exportación HTML.

**Inheritance:**[`HtmlOptions`](/slides/python-net/es/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo HtmlOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/es/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Crea un nuevo objeto HtmlOptions especificando una callback. |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/htmloptions/__init__/#) | Crea un nuevo objeto HtmlOptions para guardar en un solo archivo HTML. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/htmloptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/htmloptions/progress_callback/) | Representa un objeto de callback para guardar actualizaciones de progreso en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/htmloptions/default_regular_font/) | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura-escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/htmloptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/htmloptions/skip_java_script_links/) | Especifica si se omiten los hipervínculos con llamadas JavaScript al guardar la presentación.<br/>            Lectura/escritura **bool**. El valor predeterminado es **false**. |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/htmloptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/htmloptions/ink_options/) | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/htmloptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`html_formatter`](/slides/python-net/es/aspose.slides.export/htmloptions/html_formatter/) | Devuelve o establece la plantilla HTML.<br/>            Lectura/escritura [`IHtmlFormatter`](/slides/python-net/es/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/es/aspose.slides.export/htmloptions/disable_font_ligatures/) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras.<br/>            Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. De forma predeterminada, esta propiedad está establecida en `false`. |
| [`slide_image_format`](/slides/python-net/es/aspose.slides.export/htmloptions/slide_image_format/) | Devuelve o establece las opciones de formato de imagen de diapositiva.<br/>            Lectura/escritura [`ISlideImageFormat`](/slides/python-net/es/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/htmloptions/jpeg_quality/) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.<br/>            Lectura/escritura **int**. |
| [`pictures_compression`](/slides/python-net/es/aspose.slides.export/htmloptions/pictures_compression/) | Representa el nivel de compresión de imágenes |
| [`delete_pictures_cropped_areas`](/slides/python-net/es/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán,<br/>            si es false se serializarán en el documento (lo que puede provocar un archivo más grande) |
| [`svg_responsive_layout`](/slides/python-net/es/aspose.slides.export/htmloptions/svg_responsive_layout/) | True para excluir los atributos de ancho y alto del contenedor svg - lo que hará que el diseño sea responsivo. False - en caso contrario.<br/>            Lectura/escritura **bool**. |

### Ver también
* clase [`HtmlOptions`](/slides/python-net/es/aspose.slides.export/htmloptions)
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)