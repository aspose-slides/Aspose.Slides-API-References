---
title: ISVGOptions class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.export/isvgoptions/
---
## ISVGOptions clase

Representa una opción SVG.

El tipo ISVGOptions expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`vectorize_text`](/slides/python-net/es/aspose.slides.export/isvgoptions/vectorize_text/) | Determina si el texto en una diapositiva se guardará como gráficos.<br/>            Lectura/escritura **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/es/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Devuelve o establece el límite inferior de resolución para la rasterización de metarchivos.<br/>            Lectura/escritura **int**. |
| [`disable_3d_text`](/slides/python-net/es/aspose.slides.export/isvgoptions/disable_3d_text/) | Determina si el texto 3D está deshabilitado en SVG.<br/>            Lectura/escritura **bool**. |
| [`disable_gradient_split`](/slides/python-net/es/aspose.slides.export/isvgoptions/disable_gradient_split/) | Deshabilita la división de los degradados FromCornerX y FromCenter.<br/>            Lectura/escritura **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/es/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 carece de la capacidad de definir inserciones para marcadores.<br/>            El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema:<br/>            recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores.<br/>            Esta opción desactiva dicho comportamiento.<br/>            Lectura/escritura **bool**. |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/isvgoptions/jpeg_quality/) | Determina la calidad de codificación JPEG.<br/>            Lectura/escritura **int**. |
| [`shape_formatting_controller`](/slides/python-net/es/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas.<br/>            Lectura/escritura [`ISvgShapeFormattingController`](/slides/python-net/es/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/es/aspose.slides.export/isvgoptions/pictures_compression/) | Representa el nivel de compresión de las imágenes.<br/>            Lectura/escritura [`ISVGOptions.pictures_compression`](/slides/python-net/es/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/es/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Un indicador booleano muestra si las partes recortadas permanecen como parte del documento. Si es verdadero, las partes recortadas se eliminarán; si es falso, se serializarán en el documento (lo que puede provocar un archivo más grande).<br/>            Lectura/escritura **bool**. |
| [`use_frame_size`](/slides/python-net/es/aspose.slides.export/isvgoptions/use_frame_size/) | Determina si el marco de texto se incluirá en un área de renderizado o no.<br/>            Lectura/escritura **bool**.<br/>            El valor predeterminado es falso. |
| [`use_frame_rotation`](/slides/python-net/es/aspose.slides.export/isvgoptions/use_frame_rotation/) | Determina si se debe realizar la rotación especificada de la forma al renderizar o no.<br/>            Lectura/escritura **bool**.<br/>            El valor predeterminado es verdadero. |
| [`external_fonts_handling`](/slides/python-net/es/aspose.slides.export/isvgoptions/external_fonts_handling/) | Determina una forma de manejar fuentes cargadas externamente.<br/>            Lectura/escritura [`SvgExternalFontsHandling`](/slides/python-net/es/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/isvgoptions/ink_options/) | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/es/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras.<br/>            Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en `false`. |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)