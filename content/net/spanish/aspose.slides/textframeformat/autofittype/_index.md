---
title: AutofitType
second_title: Referencia de la API Aspose.Slides para .NET
description: Devuelve o establece el modo de ajuste automático de textos. Lectura/escritura TextAutofitTypeaspose.slides/textautofittype.
type: docs
weight: 30
url: /es/aspose.slides/textframeformat/autofittype/
---

## Propiedad TextFrameFormat.AutofitType

Devuelve o establece el modo de ajuste automático del texto. Lectura/escritura [`TextAutofitType`](../../textautofittype).

```csharp
public TextAutofitType AutofitType { get; set; }
```

### Ejemplos

El siguiente código de muestra muestra cómo redimensionar una forma para ajustar el texto en una presentación de PowerPoint.

```csharp
[C#]
 using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];
    IAutoShape autoShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
    Portion portion = new Portion("lorem ipsum...");
    portion.PortionFormat.FillFormat.SolidFillColor.Color = Color.Black;
    portion.PortionFormat.FillFormat.FillType = FillType.Solid;
    autoShape.TextFrame.Paragraphs[0].Portions.Add(portion);
    ITextFrameFormat textFrameFormat = autoShape.TextFrame.TextFrameFormat;
    textFrameFormat.AutofitType = TextAutofitType.Shape;
    pres.Save("Output-presentation.pptx", SaveFormat.Pptx);
}
```

El siguiente código de muestra muestra cómo reducir el texto en caso de desbordamiento.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];
    IAutoShape autoShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
    Portion portion = new Portion("lorem ipsum...");
    portion.PortionFormat.FillFormat.SolidFillColor.Color = Color.Black;
    portion.PortionFormat.FillFormat.FillType = FillType.Solid;
    autoShape.TextFrame.Paragraphs[0].Portions.Add(portion);
    ITextFrameFormat textFrameFormat = autoShape.TextFrame.TextFrameFormat;
    textFrameFormat.AutofitType = TextAutofitType.Normal;
    pres.Save("Output-presentation.pptx", SaveFormat.Pptx);
}
```

### Ver También

* enum [TextAutofitType](../../textautofittype)
* class [TextFrameFormat](../../textframeformat)
* namespace [Aspose.Slides](../../textframeformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->