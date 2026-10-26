---
title: RenderingOptions class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/renderingoptions/
---
## RenderingOptions clase

Proporciona opciones que controlan cómo se renderiza una presentación/diapositiva.

**Inheritance:**[`RenderingOptions`](/slides/python-net/es/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo RenderingOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/renderingoptions/__init__/#) | Constructor predeterminado. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/renderingoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/renderingoptions/progress_callback/) | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/renderingoptions/default_regular_font/) | Devuelve o establece la fuente utilizada en caso de que la fuente original no se encuentre.<br/>            Lectura/escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/renderingoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/renderingoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación.<br/>            Lectura/escritura **bool**. El valor predeterminado es **false**. |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/renderingoptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/renderingoptions/ink_options/) | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/es/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras.<br/>            Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en `false`. |

### Ver también
* clase [`RenderingOptions`](/slides/python-net/es/aspose.slides.export/renderingoptions)
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)