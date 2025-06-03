---
title: Layout
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el diseño de las Secciones de Resumen de Zoom en el marco. El valor predeterminado es GridLayout.
type: docs
weight: 10
url: /es/aspose.slides/summaryzoomframe/layout/
---

## Propiedad SummaryZoomFrame.Layout

Obtiene el diseño de las Secciones de Resumen de Zoom en el marco. El valor predeterminado es GridLayout.

```csharp
public ZoomLayout Layout { get; }
```

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de Sección de Resumen de Zoom por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ZoomLayout layout = zoomFrame.Layout;
}
```

### Véase también

* enum [ZoomLayout](../../zoomlayout)
* class [SummaryZoomFrame](../../summaryzoomframe)
* namespace [Aspose.Slides](../../summaryzoomframe)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
