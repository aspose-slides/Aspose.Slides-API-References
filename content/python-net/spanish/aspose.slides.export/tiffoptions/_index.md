---
title: TiffOptions class
second_title: Referencia API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/tiffoptions/
---
## TiffOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.

**Herencia:**[`TiffOptions`](/slides/python-net/es/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo TiffOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/tiffoptions/__init__/#) | Constructor predeterminado. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/tiffoptions/warning_callback/) | Obtiene o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/tiffoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizar el progreso del guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/tiffoptions/default_regular_font/) | Obtiene o establece la fuente usada en caso de que no se encuentre la fuente origen.<br/>            Lectura-escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/tiffoptions/gradient_style/) | Obtiene o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/tiffoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. <br/>            Lectura/escritura **bool**. The default value is **false** . |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/tiffoptions/ink_options/) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/tiffoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            Default is `false`. |
| [`image_size`](/slides/python-net/es/aspose.slides.export/tiffoptions/image_size/) | Especifica el tamaño de una imagen TIFF generada.<br/>            El valor predeterminado es 0x0, lo que significa que los tamaños de la imagen generada se calcularán en función del valor del tamaño de la diapositiva de la presentación.<br/>            Lectura/escritura **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/es/aspose.slides.export/tiffoptions/dpi_x/) | Especifica la resolución horizontal en puntos por pulgada.<br/>            Lectura/escritura **int**. |
| [`dpi_y`](/slides/python-net/es/aspose.slides.export/tiffoptions/dpi_y/) | Especifica la resolución vertical en puntos por pulgada.<br/>            Lectura/escritura **int**. |
| [`compression_type`](/slides/python-net/es/aspose.slides.export/tiffoptions/compression_type/) | Especifica el tipo de compresión.<br/>            Lectura/escritura [`TiffCompressionTypes`](/slides/python-net/es/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/es/aspose.slides.export/tiffoptions/pixel_format/) | Especifica el formato de píxel para las imágenes generadas.<br/>            Lectura/escritura [`ImagePixelFormat`](/slides/python-net/es/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/tiffoptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/es/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro.<br/>            Esta opción se aplicará solo si [`TiffOptions.compression_type`](/slides/python-net/es/aspose.slides.export/tiffoptions/compression_type) <br/>            está configurado a [`TiffCompressionTypes.CCITT4`](/slides/python-net/es/aspose.slides.export/tiffcompressiontypes/CCITT4) o [`TiffCompressionTypes.CCITT3`](/slides/python-net/es/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lectura/escritura [`BlackWhiteConversionMode`](/slides/python-net/es/aspose.slides.export/blackwhiteconversionmode).<br/>            El valor predeterminado es [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/es/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Ver también
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* clase [`TiffOptions`](/slides/python-net/es/aspose.slides.export/tiffoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)