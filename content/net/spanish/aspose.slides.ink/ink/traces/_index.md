---
title: Trazas
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene todas las trazas que contienen el elemento IInk IInkTraceaspose.slides/iinktrace. Solo lectura.
type: docs
weight: 10
url: /es/aspose.slides.ink/ink/traces/
---

## Propiedad Ink.Traces

Obtiene todas las trazas que contienen el elemento IInk [`IInkTrace`](../../iinktrace). Solo lectura.

```csharp
public IInkTrace[] Traces { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
}
```

### Véase También

* interfaz [IInkTrace](../../iinktrace)
* clase [Ink](../../ink)
* espacio de nombres [Aspose.Slides.Ink](../../ink)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->