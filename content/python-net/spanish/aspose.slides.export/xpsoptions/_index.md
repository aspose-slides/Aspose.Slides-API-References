---
title: XpsOptions class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/xpsoptions/
---
## XpsOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.

**Herencia:**[`XpsOptions`](/slides/python-net/es/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo XpsOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/xpsoptions/__init__/#) | Constructor predeterminado. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/xpsoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/xpsoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/xpsoptions/default_regular_font/) | Devuelve o establece la fuente usada en caso de que no se encuentre la fuente original.<br/>            Lectura/escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/xpsoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/xpsoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. <br/>            Lectura/escritura **bool**. El valor predeterminado es **false**. |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/xpsoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`save_metafiles_as_png`](/slides/python-net/es/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | Verdadero para convertir todos los metarchivos usados en una presentación a imágenes PNG.<br/>            Lectura/escritura **bool**. |
| [`draw_slides_frame`](/slides/python-net/es/aspose.slides.export/xpsoptions/draw_slides_frame/) | Verdadero para dibujar un marco negro alrededor de cada diapositiva.<br/>             Lectura/escritura **bool**. |


### Ver también
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* clase [`XpsOptions`](/slides/python-net/es/aspose.slides.export/xpsoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)