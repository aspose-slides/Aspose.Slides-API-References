---
title: Brush
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el Pincel para el IInkLine IInkBrushaspose.slides.ink/iinkbrush Solo lectura.
type: docs
weight: 10
url: /es/aspose.slides.ink/inktrace/brush/
---

## Propiedad InkTrace.Brush

Obtiene el Pincel para el IInkLine [`IInkBrush`](../../iinkbrush) Solo lectura.

```csharp
public IInkBrush Brush { get; }
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
}
```

### Véase también

* interfaz [IInkBrush](../../iinkbrush)
* clase [InkTrace](../../inktrace)
* espacio de nombres [Aspose.Slides.Ink](../../inktrace)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->