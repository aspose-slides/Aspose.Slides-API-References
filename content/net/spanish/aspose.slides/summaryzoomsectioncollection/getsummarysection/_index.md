---
title: GetSummarySection
second_title: Referencia de API Aspose.Sildes para .NET
description: Devuelve el elemento de la sección de zoom de resumen para la sección dada.
type: docs
weight: 90
url: /es/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---

## SummaryZoomSectionCollection.GetSummarySection método

Devuelve el elemento de la sección de zoom de resumen para la sección dada.

```csharp
public ISummaryZoomSection GetSummarySection(ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | ISection | Sección para encontrar [`ISection`](../../isection) |

### Valor de Retorno

[`ISummaryZoomSection`](../../isummaryzoomsection) o null si la colección no contiene un elemento para la sección.

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de la sección de zoom de resumen por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection selectedObject = collection.GetSummarySection(pres.Sections[2]);
}
```

### Ver También

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* interfaz [ISection](../../isection)
* clase [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../summaryzoomsectioncollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->