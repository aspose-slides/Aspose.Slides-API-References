---
title: SummaryZoomCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene ISummaryZoomSectionCollectionaspose.slides/isummaryzoomsectioncollection para el objeto Summary Zoom Frame.
type: docs
weight: 20
url: /es/aspose.slides/summaryzoomframe/summaryzoomcollection/
---

## Propiedad SummaryZoomFrame.SummaryZoomCollection

Obtiene [`ISummaryZoomSectionCollection`](../../isummaryzoomsectioncollection) para el objeto Summary Zoom Frame.

```csharp
public ISummaryZoomSectionCollection SummaryZoomCollection { get; }
```

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de la sección de resumen de zoom por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
}
```

### Véase también

* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* clase [SummaryZoomFrame](../../summaryzoomframe)
* espacio de nombres [Aspose.Slides](../../summaryzoomframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->