---
title: Traces
second_title: Aspose.Sildes para .NET Referencia de API
description: Obtiene todos los trazos contenidos en el elemento IInk IInkTraceaspose.slides/iinktrace. Solo lectura.
type: docs
weight: 10
url: /es/aspose.slides.ink/ink/traces/
---

## Propiedad Ink.Traces

Obtiene todos los trazos contenidos en el elemento IInk [`IInkTrace`](../../iinktrace). Solo lectura.

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

### Ver También

* interfaz [IInkTrace](../../iinktrace)
* clase [Ink](../../ink)
* espacio de nombres [Aspose.Slides.Ink](../../ink)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->