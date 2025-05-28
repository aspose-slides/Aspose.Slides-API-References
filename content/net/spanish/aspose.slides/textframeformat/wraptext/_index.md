---
title: WrapText
second_title: Referencia de API de Aspose.Slides para .NET
description: Verdadero si el texto está ajustado a los márgenes de TextFrames. Lectura/escritura NullableBoolaspose.slides/nullablebool.
type: docs
weight: 160
url: /es/aspose.slides/textframeformat/wraptext/
---

## Propiedad TextFrameFormat.WrapText

**Verdadero** si el texto está ajustado a los márgenes de TextFrame. Lectura/escritura [`NullableBool`](../../nullablebool).

```csharp
public NullableBool WrapText { get; set; }
```

### Ejemplos

El siguiente código de muestra muestra cómo ajustar el texto en una Presentación.

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
    textFrameFormat.WrapText = NullableBool.True;
    pres.Save("Output-presentation.pptx", SaveFormat.Pptx);
}
```

### Ver También

* enum [NullableBool](../../nullablebool)
* class [TextFrameFormat](../../textframeformat)
* namespace [Aspose.Slides](../../textframeformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->