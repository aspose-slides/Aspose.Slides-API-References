---
title: IndexOf
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve un índice del objeto SummaryZoomSection especificado.
type: docs
weight: 50
url: /es/aspose.slides/isummaryzoomsectioncollection/indexof/
---

## Método ISummaryZoomSectionCollection.IndexOf

Devuelve un índice del objeto SummaryZoomSection especificado.

```csharp
public int IndexOf(ISummaryZoomSection summaryZoomSection)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| summaryZoomSection | ISummaryZoomSection | Objeto SummaryZoomSection a encontrar [`ISummaryZoomSection`](../../isummaryzoomsection). |

### Valor de Retorno

Índice de un objeto SummaryZoomSection o -1 si el objeto SummaryZoomSection no pertenece a esta colección.

### Ejemplos

El ejemplo demuestra cómo obtener un elemento de la sección de resumen de zoom por índice:

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

### Vea También

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* namespace [Aspose.Slides](../../isummaryzoomsectioncollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->