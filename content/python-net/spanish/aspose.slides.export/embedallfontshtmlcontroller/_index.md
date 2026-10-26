---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController clase

La clase controladora de formato que se usa para incrustar todas las fuentes de la presentación en formato WOFF.

El tipo EmbedAllFontsHtmlController expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Crea una nueva instancia |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Crea una nueva instancia |

## Métodos

| Método | Descripción |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Llamado para escribir la cabecera del documento html. Se llama una vez por conversión de presentación. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Llamado para escribir el pie del documento html. Se llama una vez por conversión de presentación. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Llamado para escribir la cabecera de la diapositiva html. Se llama una vez por cada diapositiva. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Llamado para escribir el pie de la diapositiva html. Se llama una vez por cada diapositiva. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Llamado antes del renderizado de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se completará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Llamado antes del renderizado de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se completará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Escribe todas las fuentes contenidas en [`Presentation`](/slides/python-net/es/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Escribe los datos como base64 dentro del propio documento HTML |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)