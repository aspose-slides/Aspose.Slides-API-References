---
title: SummaryZoomCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: ObtieneISummaryZoomSectionCollectionaspose.slides/isummaryzoomsectioncollection para el objeto Cuadro de zoom de resumen.
type: docs
weight: 20
url: /es/aspose.slides/summaryzoomframe/summaryzoomcollection/
---
## SummaryZoomFrame.SummaryZoomCollection property

Obtiene[`ISummaryZoomSectionCollection`](../../isummaryzoomsectioncollection) para el objeto Cuadro de zoom de resumen.

```csharp
public ISummaryZoomSectionCollection SummaryZoomCollection { get; }
```

### Ejemplos

El ejemplo demuestra cómo obtener el elemento Sección de zoom de resumen por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
}
```

### Ver también

* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* class [SummaryZoomFrame](../../summaryzoomframe)
* espacio de nombres [Aspose.Slides](../../summaryzoomframe)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
