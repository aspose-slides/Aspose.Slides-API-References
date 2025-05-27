---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides para .NET Referencia de la API
description: La clase controlador de formato para usar para incrustar todas las fuentes de presentación en formato WOFF.
type: docs
weight: 3590
url: /es/aspose.slides.export/embedallfontshtmlcontroller/
---

## Clase EmbedAllFontsHtmlController

La clase controlador de formato para usar para incrustar todas las fuentes de presentación en formato WOFF.

```csharp
public class EmbedAllFontsHtmlController : IHtmlFormattingController
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor)() | Crea una nueva instancia |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor_1)(string[]) | Crea una nueva instancia |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [WriteAllFonts](../../aspose.slides.export/embedallfontshtmlcontroller/writeallfonts)(IHtmlGenerator, IPresentation) | Escribe todas las fuentes contenidas en [`Presentation`](../../aspose.slides/presentation). |
| virtual [WriteDocumentEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentend)(IHtmlGenerator, IPresentation) | Se llama para escribir el pie de página del documento html. Se llama una vez por conversión de presentación. |
| virtual [WriteDocumentStart](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentstart)(IHtmlGenerator, IPresentation) | Se llama para escribir el encabezado del documento html. Se llama una vez por conversión de presentación. |
| virtual [WriteFont](../../aspose.slides.export/embedallfontshtmlcontroller/writefont)(IHtmlGenerator, IFontData, IFontData, string, string, byte[]) | Escribe datos como base64 en el mismo documento HTML |
| virtual [WriteShapeEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapeend)(IHtmlGenerator, IShape) | Se llama antes del renderizado de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de imagen de la diapositiva actual se finalizará, se insertará un fragmento html y se comenzará una nueva imagen sobre la anterior. |
| virtual [WriteShapeStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapestart)(IHtmlGenerator, IShape) | Se llama antes del renderizado de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de imagen de la diapositiva actual se finalizará, se insertará un fragmento html y se comenzará una nueva imagen sobre la anterior. |
| virtual [WriteSlideEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeslideend)(IHtmlGenerator, ISlide) | Se llama para escribir el pie de página de la diapositiva html. Se llama una vez por cada diapositiva. |
| virtual [WriteSlideStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeslidestart)(IHtmlGenerator, ISlide) | Se llama para escribir el encabezado de la diapositiva html. Se llama una vez por cada diapositiva. |

### Véase También

* interfaz [IHtmlFormattingController](../ihtmlformattingcontroller)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->