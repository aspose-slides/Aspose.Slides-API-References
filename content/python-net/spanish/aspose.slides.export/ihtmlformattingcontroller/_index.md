---
title: IHtmlFormattingController class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController clase

Controla la generación de un archivo html.

El tipo IHtmlFormattingController expone los siguientes miembros:

## Métodos

| Método | Descripción |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Se llama para escribir el encabezado del documento html. Se llama una vez por conversión de presentación. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Se llama para escribir el pie del documento html. Se llama una vez por conversión de presentación. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Se llama para escribir el encabezado de la diapositiva html. Se llama una vez por cada diapositiva. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Se llama para escribir el pie de la diapositiva html. Se llama una vez por cada diapositiva. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior. |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)