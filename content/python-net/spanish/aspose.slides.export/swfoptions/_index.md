---
title: SwfOptions class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/swfoptions/
---
## SwfOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.

**Herencia:**[`SwfOptions`](/slides/python-net/es/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo SwfOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/swfoptions/__init__/#) | Constructor predeterminado. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/swfoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/swfoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/swfoptions/default_regular_font/) | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura-escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/swfoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/swfoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. <br/>            Lectura/escritura **bool**. El valor predeterminado es **false**. |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/swfoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`compressed`](/slides/python-net/es/aspose.slides.export/swfoptions/compressed/) | Especifica si el documento SWF generado debe comprimirse o no.<br/>            El valor predeterminado es `true`. |
| [`viewer_included`](/slides/python-net/es/aspose.slides.export/swfoptions/viewer_included/) | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no.<br/>            El valor predeterminado es `true`. |
| [`show_page_border`](/slides/python-net/es/aspose.slides.export/swfoptions/show_page_border/) | Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true. |
| [`show_full_screen`](/slides/python-net/es/aspose.slides.export/swfoptions/show_full_screen/) | Mostrar/ocultar botón de pantalla completa. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [`show_page_stepper`](/slides/python-net/es/aspose.slides.export/swfoptions/show_page_stepper/) | Mostrar/ocultar selector de página. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [`show_search`](/slides/python-net/es/aspose.slides.export/swfoptions/show_search/) | Mostrar/ocultar sección de búsqueda. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [`show_top_pane`](/slides/python-net/es/aspose.slides.export/swfoptions/show_top_pane/) | Mostrar/ocultar todo el panel superior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [`show_bottom_pane`](/slides/python-net/es/aspose.slides.export/swfoptions/show_bottom_pane/) | Mostrar/ocultar panel inferior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [`show_left_pane`](/slides/python-net/es/aspose.slides.export/swfoptions/show_left_pane/) | Mostrar/ocultar panel izquierdo. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [`start_open_left_pane`](/slides/python-net/es/aspose.slides.export/swfoptions/start_open_left_pane/) | Comenzar con el panel izquierdo abierto. Puede sobrescribirse en flashvars. El valor predeterminado es false. |
| [`enable_context_menu`](/slides/python-net/es/aspose.slides.export/swfoptions/enable_context_menu/) | Habilitar/deshabilitar el menú contextual. El valor predeterminado es true. |
| [`logo_image_bytes`](/slides/python-net/es/aspose.slides.export/swfoptions/logo_image_bytes/) | Imagen que se mostrará como logotipo en la esquina superior derecha del visor.<br/>            La imagen debe ser PNG de 32x64 píxeles, de lo contrario el logotipo puede mostrarse incorrectamente. |
| [`logo_link`](/slides/python-net/es/aspose.slides.export/swfoptions/logo_link/) | Obtiene o establece la dirección completa del hipervínculo para un logotipo.<br/>            Sólo tiene efecto si se especifica un [`SwfOptions.logo_image_bytes`](/slides/python-net/es/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/swfoptions/jpeg_quality/) | Especifica la calidad de las imágenes JPEG.<br/>            El valor predeterminado es 95. |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/swfoptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). <br/>            Esta propiedad no admite asignar objetos del tipo [`HandoutLayoutingOptions`](/slides/python-net/es/aspose.slides.export/handoutlayoutingoptions) |

### Ver también
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* clase [`SwfOptions`](/slides/python-net/es/aspose.slides.export/swfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)