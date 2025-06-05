---
title: Brush
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene Brush para el IInkLine IInkBrushaspose.slides.ink/iinkbrush solo de lectura.
type: docs
weight: 10
url: /es/aspose.slides.ink/iinktrace/brush/
---

## Propiedad IInkTrace.Brush

Obtiene Brush para el IInkLine [`IInkBrush`](../../iinkbrush) solo de lectura.

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

### Véase También

* interfaz [IInkBrush](../../iinkbrush)
* interfaz [IInkTrace](../../iinktrace)
* espacio de nombres [Aspose.Slides.Ink](../../iinktrace)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->