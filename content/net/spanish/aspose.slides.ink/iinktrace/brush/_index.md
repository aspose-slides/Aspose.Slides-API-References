---
title: Brush
second_title: Referencia de la API Aspose.Slides para .NET
description: Obtiene el Pincel para el IInkLine IInkBrushaspose.slides.ink/iinkbrush Solo lectura.
type: docs
weight: 10
url: /es/aspose.slides.ink/iinktrace/brush/
---

## Propiedad IInkTrace.Brush

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

* interfaz [IInkBrush](../../iinkbrush)
* interfaz [IInkTrace](../../iinktrace)
* espacio de nombres [Aspose.Slides.Ink](../../iinktrace)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->