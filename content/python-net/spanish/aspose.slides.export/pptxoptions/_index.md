---
title: PptxOptions class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/pptxoptions/
---
## PptxOptions clase

Representa opciones para guardar presentaciones OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Herencia:**[`PptxOptions`](/slides/python-net/es/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo PptxOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/pptxoptions/__init__/#) | Crea una nueva instancia de PptxOptions |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/pptxoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/pptxoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/pptxoptions/default_regular_font/) | Devuelve o establece la fuente utilizada en caso de que la fuente origen no se encuentre.<br/>            Lectura/escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/pptxoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/pptxoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación.<br/>            Lectura/escritura **bool**. El valor predeterminado es **false**. |
| [`conformance`](/slides/python-net/es/aspose.slides.export/pptxoptions/conformance/) | Especifica la clase de conformidad a la que el documento Presentation se ajusta.<br/>            El valor predeterminado es [`Conformance.ECMA_376_2006`](/slides/python-net/es/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/es/aspose.slides.export/pptxoptions/zip_64_mode/) | Especifica si se utiliza el formato ZIP64 para el documento Presentation.<br/>            El valor predeterminado es [`Zip64Mode.IF_NECESSARY`](/slides/python-net/es/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/es/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Especifica si la miniatura de la presentación se actualizará.<br/>            Lectura/escritura **bool**.<br/>            El valor predeterminado es **true**. |
| [`compression_level`](/slides/python-net/es/aspose.slides.export/pptxoptions/compression_level/) | Especifica el nivel de compresión utilizado al guardar el documento de presentación.<br/>            El valor predeterminado es [`CompressionLevel.LEVEL6`](/slides/python-net/es/aspose.slides.export/compressionlevel/LEVEL6). |


### Ver también
* clase [`PptxOptions`](/slides/python-net/es/aspose.slides.export/pptxoptions)
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)