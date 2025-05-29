---
title: Tamaño
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene o establece el tamaño del pincel para una línea en puntos.
type: docs
weight: 20
url: /es/aspose.slides.ink/iinkbrush/size/
---

## Propiedad IInkBrush.Size

Obtiene o establece el tamaño del pincel para una línea en puntos.

```csharp
public SizeF Size { get; set; }
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
    SizeF brushSize = brush.Size;
    brush.Size = new SizeF(5f, 10f);
}
```

### Ver También

* interfaz [IInkBrush](../../iinkbrush)
* espacio de nombres [Aspose.Slides.Ink](../../iinkbrush)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->