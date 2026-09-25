---
title: ITiffOptions class
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides.export/itiffoptions/
---
## ITiffOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.

El tipo ITiffOptions expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/es/aspose.slides.export/itiffoptions/image_size/) | Especifica el tamaño de una imagen TIFF generada.<br/>            El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán en función del valor del tamaño de la diapositiva de la presentación.<br/>            Lectura/escritura [`Size`](/slides/python-net/es/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/es/aspose.slides.export/itiffoptions/dpi_x/) | Especifica la resolución horizontal en puntos por pulgada.<br/>            Lectura/escritura **int**. |
| [`dpi_y`](/slides/python-net/es/aspose.slides.export/itiffoptions/dpi_y/) | Especifica la resolución vertical en puntos por pulgada.<br/>            Lectura/escritura **int**. |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/itiffoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`compression_type`](/slides/python-net/es/aspose.slides.export/itiffoptions/compression_type/) | Especifica el tipo de compresión.<br/>            Lectura/escritura [`TiffCompressionTypes`](/slides/python-net/es/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/es/aspose.slides.export/itiffoptions/pixel_format/) | Especifica el formato de píxel para las imágenes generadas.<br/>            Lectura/escritura [`ImagePixelFormat`](/slides/python-net/es/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/itiffoptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/es/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Especifica el algoritmo para convertir una imagen en color a una imagen en blanco y negro.<br/>            Esta opción se aplicará solo si [`ITiffOptions.compression_type`](/slides/python-net/es/aspose.slides.export/itiffoptions/compression_type)<br/>            está configurado a [`TiffCompressionTypes.CCITT4`](/slides/python-net/es/aspose.slides.export/tiffcompressiontypes/CCITT4) o [`TiffCompressionTypes.CCITT3`](/slides/python-net/es/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lectura/escritura [`BlackWhiteConversionMode`](/slides/python-net/es/aspose.slides.export/blackwhiteconversionmode).<br/>            El valor predeterminado es [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/es/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/itiffoptions/ink_options/) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Véase también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)