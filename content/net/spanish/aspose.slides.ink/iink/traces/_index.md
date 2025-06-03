---
title: Traces
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene todas las trazas que contiene el elemento IInk IInkTraceaspose.slides.ink/iinktrace. Solo lectura.
type: docs
weight: 20
url: /es/aspose.slides.ink/iink/traces/
---

## Propiedad IInk.Traces

Obtiene todas las trazas que contiene el elemento IInk [`IInkTrace`](../../iinktrace). Solo lectura.

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
* interfaz [IInk](../../iink)
* espacio de nombres [Aspose.Slides.Ink](../../iink)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->