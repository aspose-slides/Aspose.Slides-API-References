---
title: IMathPortion
second_title: Aspose.Sildes para .NET API Referencia
description: Representa una porción con contexto matemático dentro.
type: docs
weight: 8160
url: /es/aspose.slides.mathtext/imathportion/
---

## Interfaz IMathPortion

Representa una porción con contexto matemático dentro.

```csharp
public interface IMathPortion
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MathParagraph](../../aspose.slides.mathtext/imathportion/mathparagraph) { get; } | Párrafo matemático |

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

* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->