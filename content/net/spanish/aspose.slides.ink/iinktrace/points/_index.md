---
title: Puntos
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene puntos para el IInkLine PointF de solo lectura.
type: docs
weight: 20
url: /es/aspose.slides.ink/iinktrace/points/
---

## Propiedad IInkTrace.Points

Obtiene puntos para el IInkLine PointF de solo lectura.

```csharp
public PointF[] Points { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
    PointF[] points = traces[0].Points;
}
```

### Vea También

* interfaz [IInkTrace](../../iinktrace)
* espacio de nombres [Aspose.Slides.Ink](../../iinktrace)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->