---
title: IMathPortion
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una porción con contexto matemático en su interior.
type: docs
weight: 8160
url: /es/aspose.slides.mathtext/imathportion/
---

## Interfaz IMathPortion

Representa una porción con contexto matemático en su interior.

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

### Véase también

* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->