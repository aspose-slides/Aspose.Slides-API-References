---
title: MathPortion
second_title: Referencia de API de Aspose.Slides para .NET
description: Inicializa una nueva instancia de la clase MathPortion.
type: docs
weight: 10
url: /es/aspose.slides.mathtext/mathportion/mathportion/
---

## Constructor de MathPortion

Inicializa una nueva instancia de la clase MathPortion.

```csharp
public MathPortion()
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape shape = pres.Slides[0].Shapes.AddMathShape(0, 0, 300, 50);
    IParagraph paragraph = shape.TextFrame.Paragraphs[0];
    MathPortion mathPortion = new MathPortion();
    paragraph.Portions.Add(mathPortion);
}
```

### Ver También

* clase [MathPortion](../../mathportion)
* espacio de nombres [Aspose.Slides.MathText](../../mathportion)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
