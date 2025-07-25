---
title: RemoveSummaryZoomSection
second_title: Aspose.Slides para .NET Referencia de API
description: Eliminar objeto de Sección de Resumen Zoom de la colección.
type: docs
weight: 60
url: /es/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---

## ISummaryZoomSectionCollection.RemoveSummaryZoomSection método

Eliminar objeto de Sección de Resumen Zoom de la colección.

```csharp
public void RemoveSummaryZoomSection(ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | ISection | Sección para la cual se debe eliminar el elemento de Sección de Resumen Zoom [`ISection`](../../isection). |

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de Sección de Resumen Zoom por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.RemoveSummaryZoomSection(pres.Sections[1]);
}
```

### Ver También

* interfaz [ISection](../../isection)
* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../isummaryzoomsectioncollection)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->