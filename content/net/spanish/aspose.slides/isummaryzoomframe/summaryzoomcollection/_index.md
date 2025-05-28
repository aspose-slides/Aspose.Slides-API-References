---
title: ResumenColecciónZoom
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene ISummaryZoomSectionCollectionaspose.slides/isummaryzoomsectioncollection para el objeto Marco de Resumen Zoom.
type: docs
weight: 30
url: /es/aspose.slides/isummaryzoomframe/summaryzoomcollection/
---

## Propiedad ISummaryZoomFrame.SummaryZoomCollection

Obtiene [`ISummaryZoomSectionCollection`](../../isummaryzoomsectioncollection) para el objeto Marco de Resumen Zoom.

```csharp
public ISummaryZoomSectionCollection SummaryZoomCollection { get; }
```

### Ejemplos

El ejemplo demuestra cómo obtener un elemento de Sección de Resumen Zoom por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
}
```

### Véase También

* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* interfaz [ISummaryZoomFrame](../../isummaryzoomframe)
* namespace [Aspose.Slides](../../isummaryzoomframe)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->