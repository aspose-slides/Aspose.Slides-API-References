---
title: IndexOf
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve un índice del objeto SummaryZoomSection especificado.
type: docs
weight: 100
url: /es/aspose.slides/summaryzoomsectioncollection/indexof/
---

## Método SummaryZoomSectionCollection.IndexOf

Devuelve un índice del objeto SummaryZoomSection especificado.

```csharp
public int IndexOf(ISummaryZoomSection summaryZoomSection)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| summaryZoomSection | ISummaryZoomSection | Objeto SummaryZoomSection para encontrar [`ISummaryZoomSection`](../../isummaryzoomsection). |

### Valor de Retorno

Índice de un objeto SummaryZoomSection o -1 si el objeto SummaryZoomSection no pertenece a esta colección.

### Ejemplos

El ejemplo demuestra cómo obtener un elemento de Summary Zoom Section por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection selectedObject = collection.GetSummarySection(pres.Sections[2]);
    int idx = collection.IndexOf(selectedObject);
}
```

### Ver También

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* clase [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../summaryzoomsectioncollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->