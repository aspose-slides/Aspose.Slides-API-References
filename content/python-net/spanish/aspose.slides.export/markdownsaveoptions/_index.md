---
title: MarkdownSaveOptions class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions clase

Representa opciones que controlan cómo se debe guardar la presentación en markdown.

**Herencia:**[`MarkdownSaveOptions`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo MarkdownSaveOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Devuelve o establece la fuente usada en caso de que no se encuentre la fuente origen.<br/>            Lectura/escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación.<br/>            Lectura/escritura **bool**. El valor predeterminado es **false**. |
| [`export_type`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/export_type/) | Especifica la especificación markdown para convertir la presentación.<br/>            El valor predeterminado es `TextOnly`. |
| [`base_path`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/base_path/) | Especifica la ruta base donde se guardará el documento con recursos.<br/>            El valor predeterminado es el directorio actual de la aplicación. |
| [`images_save_folder_name`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Especifica el nombre de la carpeta para guardar imágenes.<br/>            El valor predeterminado es `Images`. |
| [`new_line_type`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/new_line_type/) | Especifica si el documento generado debe tener saltos de línea \\r(Macintosh), \\n(Unix) o \\r\\n(Windows).<br/>            El valor predeterminado es `Unix`. |
| [`show_comments`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/show_comments/) | Especifica si el documento generado debe mostrar comentarios o no.<br/>            El valor predeterminado es `false`. |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`show_slide_number`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Especifica si el documento generado debe mostrar el número de cada diapositiva o no.<br/>            El valor predeterminado es `false`. |
| [`flavor`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/flavor/) | Especifica la especificación markdown para convertir la presentación.<br/>            El valor predeterminado es `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown.<br/>            El formato debe incluir el marcador \"{0}\", que será reemplazado por el índice de la diapositiva durante la exportación.<br/>            Ejemplo: \"# Slide {0}\" producirá \"# Slide 1\", \"# Slide 2\", etc. |
| [`handle_repeated_spaces`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Si se establece en `true`, elimina las líneas vacías o que solo contienen espacios en blanco del resultado final de Markdown.<br/>            El valor predeterminado es `false`. |

### Ver también
* clase [`MarkdownSaveOptions`](/slides/python-net/es/aspose.slides.export/markdownsaveoptions)
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)