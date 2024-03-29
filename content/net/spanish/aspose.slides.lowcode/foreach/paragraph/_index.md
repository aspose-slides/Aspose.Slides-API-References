---
title: Paragraph
second_title: Referencia de la API de Aspose.Slides para .NET
description: Iterar cadaParagraphaspose.slides.lowcode/foreach/paragraph en elPresentationaspose.slides/presentation .  Las formas se repetirán en todo tipo de diapositivasSlideaspose.slides.lowcode/foreach/slide MasterSlideaspose.slides.lowcode/foreach/masterslide yLayoutSlideaspose.slides.lowcode/foreach/layoutslide
type: docs
weight: 30
url: /es/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach.Paragraph method

Iterar cada`Paragraph` en el[`Presentation`](../../../aspose.slides/presentation) .  Las formas se repetirán en todo tipo de diapositivas:[`Slide`](../slide) ,[`MasterSlide`](../masterslide) y[`LayoutSlide`](../layoutslide)

```csharp
public static void Paragraph(Presentation pres, ForEachParagraphCallback forEachParagraph)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pres | Presentation | Presentación para iterar párrafos |
| forEachParagraph | ForEachParagraphCallback | Devolución de llamada que se invocará para cada párrafo |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Paragraph(pres, (para, slide, index) =>
    {
        System.Console.WriteLine($"{para.Text}, index: {index}");
    });
}        
```

### Ver también

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachParagraphCallback](../../foreach.foreachparagraphcallback)
* class [ForEach](../../foreach)
* espacio de nombres [Aspose.Slides.LowCode](../../foreach)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
