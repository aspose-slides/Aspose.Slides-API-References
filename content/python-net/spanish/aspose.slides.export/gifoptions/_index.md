---
title: GifOptions class
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/gifoptions/
---
## GifOptions clase

Representa opciones de exportación de GIF.

**Herencia:**[`GifOptions`](/slides/python-net/es/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo GifOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/gifoptions/__init__/#) | Inicializa una nueva instancia de la clase GifOptions. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/gifoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/gifoptions/progress_callback/) | Representa un objeto de devolución de llamada para guardar actualizaciones del progreso en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/gifoptions/default_regular_font/) | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen.<br/>            Lectura/escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/gifoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/gifoptions/skip_java_script_links/) | Especifica si se omiten los hipervínculos con llamadas JavaScript al guardar la presentación. <br/>            Lectura/escritura **bool**. El valor predeterminado es **false** . |
| [`frame_size`](/slides/python-net/es/aspose.slides.export/gifoptions/frame_size/) | Obtiene o establece el tamaño del fotograma. |
| [`export_hidden_slides`](/slides/python-net/es/aspose.slides.export/gifoptions/export_hidden_slides/) | Determina si las diapositivas ocultas se exportarán.<br/>            El valor predeterminado es false. |
| [`transition_fps`](/slides/python-net/es/aspose.slides.export/gifoptions/transition_fps/) | Obtiene o establece los FPS de transición [frames/sec]<br/>            El valor predeterminado es 25. |
| [`default_delay`](/slides/python-net/es/aspose.slides.export/gifoptions/default_delay/) | Obtiene o establece el tiempo de retardo predeterminado [ms]. Este valor se usará si [`ISlideShowTransition.advance_after_time`](/slides/python-net/es/aspose.slides/islideshowtransition/advance_after_time) no está configurado.<br/>            El valor predeterminado es 1000. |

### Ver también
* clase [`GifOptions`](/slides/python-net/es/aspose.slides.export/gifoptions)
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)