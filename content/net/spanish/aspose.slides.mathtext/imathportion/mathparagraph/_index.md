---
title: MathParagraph
second_title: Referencia de la API de Aspose.Slides para .NET
description: Párrafo matemático
type: docs
weight: 10
url: /es/aspose.slides.mathtext/imathportion/mathparagraph/
---

## Propiedad IMathPortion.MathParagraph

Párrafo matemático

```csharp
public IMathParagraph MathParagraph { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape shape = pres.Slides[0].Shapes.AddMathShape(0, 0, 300, 50);
    IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
    mathParagraph.Add(new MathBlock(new MathematicalText("x+y")));
}
```

### Véase También

* interfaz [IMathParagraph](../../imathparagraph)
* interfaz [IMathPortion](../../imathportion)
* espacio de nombres [Aspose.Slides.MathText](../../imathportion)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->