---
title: Color
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene o establece el color del pincel para una línea.
type: docs
weight: 10
url: /es/aspose.slides.ink/inkbrush/color/
---

## Propiedad InkBrush.Color

Obtiene o establece el color del pincel para una línea.

```csharp
public Color Color { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
    IInkBrush brush = traces[0].Brush;
    Color brushColor = brush.Color;
    brush.Color = Color.Red;
}
```

### Ver También

* clase [InkBrush](../../inkbrush)
* espacio de nombres [Aspose.Slides.Ink](../../inkbrush)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->