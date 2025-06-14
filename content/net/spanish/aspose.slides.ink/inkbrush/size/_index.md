---
title: Size
second_title: Referencia de la API Aspose.Slidess para .NET
description: Obtiene o establece el tamaño del pincel para una línea en puntos.
type: docs
weight: 20
url: /es/aspose.slides.ink/inkbrush/size/
---

## InkBrush.Size property

Obtiene o establece el tamaño del pincel para una línea en puntos.

```csharp
public SizeF Size { get; set; }
```

### Examples

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
    IInkBrush brush = traces[0].Brush;
    SizeF brushSize = brush.Size;
    brush.Size = new SizeF(5f, 10f);
}
```

### See Also

* class [InkBrush](../../inkbrush)
* namespace [Aspose.Slides.Ink](../../inkbrush)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->