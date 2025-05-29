---
title: Puntos
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene puntos para el IInkLine PointF Solo lectura.
type: docs
weight: 20
url: /es/aspose.slides.ink/inktrace/points/
---

## Propiedad InkTrace.Points

Obtiene puntos para el IInkLine PointF Solo lectura.

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

### Ver También

* clase [InkTrace](../../inktrace)
* espacio de nombres [Aspose.Slides.Ink](../../inktrace)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->