---
title: IHtmlFormattingController
second_title: Referencia de API de Aspose.Slides para .NET
description: Controla la generación de un archivo html.
type: docs
weight: 3780
url: /es/aspose.slides.export/ihtmlformattingcontroller/
---

## Interfaz IHtmlFormattingController

Controla la generación de un archivo html.

```csharp
public interface IHtmlFormattingController
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [WriteDocumentEnd](../../aspose.slides.export/ihtmlformattingcontroller/writedocumentend)(IHtmlGenerator, IPresentation) | Se llama para escribir el pie de página del documento html. Se llama una vez por conversión de presentación. |
| [WriteDocumentStart](../../aspose.slides.export/ihtmlformattingcontroller/writedocumentstart)(IHtmlGenerator, IPresentation) | Se llama para escribir el encabezado del documento html. Se llama una vez por conversión de presentación. |
| [WriteShapeEnd](../../aspose.slides.export/ihtmlformattingcontroller/writeshapeend)(IHtmlGenerator, IShape) | Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento de html agregado y se comenzará una nueva imagen encima de la anterior. |
| [WriteShapeStart](../../aspose.slides.export/ihtmlformattingcontroller/writeshapestart)(IHtmlGenerator, IShape) | Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento de html agregado y se comenzará una nueva imagen encima de la anterior. |
| [WriteSlideEnd](../../aspose.slides.export/ihtmlformattingcontroller/writeslideend)(IHtmlGenerator, ISlide) | Se llama para escribir el pie de página de la diapositiva html. Se llama una vez por cada diapositiva. |
| [WriteSlideStart](../../aspose.slides.export/ihtmlformattingcontroller/writeslidestart)(IHtmlGenerator, ISlide) | Se llama para escribir el encabezado de la diapositiva html. Se llama una vez por cada diapositiva. |

### Ver También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->