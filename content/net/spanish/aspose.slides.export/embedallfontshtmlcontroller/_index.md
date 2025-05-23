---
title: EmbedAllFontsHtmlController
second_title: Referencia de la API de Aspose.Slides para .NET
description: La clase de controlador de formato que se usará para incrustar todas las fuentes de presentación en formato WOFF.
type: docs
weight: 3490
url: /es/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController class

La clase de controlador de formato que se usará para incrustar todas las fuentes de presentación en formato WOFF.

```csharp
public class EmbedAllFontsHtmlController : IHtmlFormattingController
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor)() | Crea nueva instancia |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor_1)(string[]) | Crea nueva instancia |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [WriteAllFonts](../../aspose.slides.export/embedallfontshtmlcontroller/writeallfonts)(IHtmlGenerator, IPresentation) | Escribir todas las fuentes contenidas en[`Presentation`](../../aspose.slides/presentation) . |
| virtual [WriteDocumentEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentend)(IHtmlGenerator, IPresentation) | Llamado para escribir el pie de página del documento html. Llamado una vez por conversión de presentación. |
| virtual [WriteDocumentStart](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentstart)(IHtmlGenerator, IPresentation) | Llamado para escribir el encabezado del documento html. Llamado una vez por conversión de presentación. |
| virtual [WriteFont](../../aspose.slides.export/embedallfontshtmlcontroller/writefont)(IHtmlGenerator, IFontData, IFontData, string, string, byte[]) | Escribe datos como base64 en el propio documento HTML |
| virtual [WriteShapeEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapeend)(IHtmlGenerator, IShape) | Llamado antes de la representación de la forma. Llamado una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual finalizará, se insertará un fragmento html agregado y se iniciará una nueva imagen encima de la anterior. |
| virtual [WriteShapeStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapestart)(IHtmlGenerator, IShape) | Llamado antes de la representación de la forma. Llamado una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual finalizará, se insertará un fragmento html agregado y se iniciará una nueva imagen encima de la anterior. |
| virtual [WriteSlideEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeslideend)(IHtmlGenerator, ISlide) | Llamado para escribir el pie de página de la diapositiva html. Llamado una vez por cada una de las diapositivas. |
| virtual [WriteSlideStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeslidestart)(IHtmlGenerator, ISlide) | Llamado para escribir encabezado de diapositiva html. Llamado una vez por cada una de las diapositivas. |

### Ver también

* interface [IHtmlFormattingController](../ihtmlformattingcontroller)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
