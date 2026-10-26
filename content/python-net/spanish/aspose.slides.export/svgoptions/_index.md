---
title: SVGOptions class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/svgoptions/
---
## Clase SVGOptions

Representa una opción SVG.

**Herencia:**[`SVGOptions`](/slides/python-net/es/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo SVGOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/svgoptions/__init__/#) | Inicializa una nueva instancia de la clase SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/es/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Inicializa una nueva instancia de la clase SVGOptions especificando el objeto controlador de incrustación de enlaces. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/svgoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/svgoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/svgoptions/default_regular_font/) | Devuelve o establece la fuente usada en caso de que no se encuentre la fuente original.<br/>            Lectura/escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/svgoptions/gradient_style/) | Devuelve o establece el estilo visual del gradiente.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/svgoptions/skip_java_script_links/) | Especifica si se omiten hipervínculos con llamadas JavaScript al guardar la presentación. <br/>            Lectura/escritura **bool**. El valor predeterminado es **false** . |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/svgoptions/ink_options/) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/es/aspose.slides.export/svgoptions/use_frame_size/) | Determina si el marco de texto se incluirá en un área de renderizado o no.<br/>            Lectura/escritura **bool**.<br/>            El valor predeterminado es false. |
| [`use_frame_rotation`](/slides/python-net/es/aspose.slides.export/svgoptions/use_frame_rotation/) | Determina si se realiza la rotación especificada de la forma al renderizar o no.<br/>            Lectura/escritura **bool**.<br/>            El valor predeterminado es true. |
| [`vectorize_text`](/slides/python-net/es/aspose.slides.export/svgoptions/vectorize_text/) | Determina si el texto en una diapositiva se guardará como gráficos.<br/>            Lectura/escritura **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/es/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Devuelve o establece el límite de resolución inferior para la rasterización de metafiles.<br/>            Lectura/escritura **int**. |
| [`disable_3d_text`](/slides/python-net/es/aspose.slides.export/svgoptions/disable_3d_text/) | Determina si el texto 3D está deshabilitado en SVG.<br/>            Lectura/escritura **bool**. |
| [`disable_gradient_split`](/slides/python-net/es/aspose.slides.export/svgoptions/disable_gradient_split/) | Deshabilita la división de los gradientes FromCornerX y FromCenter.<br/>            Lectura/escritura **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/es/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 carece de la capacidad de definir inserciones para marcadores.<br/>            El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema:<br/>            recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores.<br/>            Esta opción desactiva dicho comportamiento.<br/>            Lectura/escritura **bool**. |
| [`default`](/slides/python-net/es/aspose.slides.export/svgoptions/default/) | Devuelve la configuración predeterminada.<br/>            Solo lectura [`SVGOptions`](/slides/python-net/es/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/es/aspose.slides.export/svgoptions/simple/) | Devuelve la configuración para la generación del archivo SVG más simple y pequeño.<br/>            Solo lectura [`SVGOptions`](/slides/python-net/es/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/es/aspose.slides.export/svgoptions/wysiwyg/) | Devuelve la configuración para la generación del archivo SVG más preciso.<br/>            Solo lectura [`SVGOptions`](/slides/python-net/es/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/svgoptions/jpeg_quality/) | Determina la calidad de codificación JPEG.<br/>            Lectura/escritura **int**. |
| [`shape_formatting_controller`](/slides/python-net/es/aspose.slides.export/svgoptions/shape_formatting_controller/) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas.<br/>            Lectura/escritura [`ISvgShapeFormattingController`](/slides/python-net/es/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/es/aspose.slides.export/svgoptions/pictures_compression/) | Representa el nivel de compresión de imágenes |
| [`delete_pictures_cropped_areas`](/slides/python-net/es/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas <br/>            se eliminarán, si es false se serializarán en el documento (lo que puede conducir a un <br/>            archivo más grande) |
| [`external_fonts_handling`](/slides/python-net/es/aspose.slides.export/svgoptions/external_fonts_handling/) | Determina la forma de manejar fuentes cargadas externamente.<br/>            Lectura/escritura [`SvgExternalFontsHandling`](/slides/python-net/es/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/es/aspose.slides.export/svgoptions/disable_font_ligatures/) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras.<br/>            Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en `false`. |

### Ver también
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* clase [`SVGOptions`](/slides/python-net/es/aspose.slides.export/svgoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)