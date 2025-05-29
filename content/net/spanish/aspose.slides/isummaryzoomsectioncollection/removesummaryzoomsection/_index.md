---
title: RemoveSummaryZoomSection
second_title: Referencia de API de Aspose.Slides para .NET
description: Eliminar objeto de Sección de Zoom Resumido de la colección.
type: docs
weight: 60
url: /es/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---

## ISummaryZoomSectionCollection.RemoveSummaryZoomSection método

Eliminar objeto de Sección de Zoom Resumido de la colección.

```csharp
public void RemoveSummaryZoomSection(ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | ISection | Sección para la cual se debe eliminar el elemento de Sección de Zoom Resumido [`ISection`](../../isection). |

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de Sección de Zoom Resumido por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.RemoveSummaryZoomSection(pres.Sections[1]);
}
```

### Véase También

* interfaz [ISection](../../isection)
* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* namespace [Aspose.Slides](../../isummaryzoomsectioncollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->