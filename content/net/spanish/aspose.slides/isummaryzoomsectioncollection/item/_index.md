---
title: Item
second_title: Aspose.Sildes para .NET Referencia de API
description: Obtiene el elemento en el índice especificado. Solo lectura ISummaryZoomSectionaspose.slides/isummaryzoomsection.
type: docs
weight: 10
url: /es/aspose.slides/isummaryzoomsectioncollection/item/
---

## ISummaryZoomSectionCollection indexer

Obtiene el elemento en el índice especificado. Solo lectura [`ISummaryZoomSection`](../../isummaryzoomsection).

```csharp
public ISummaryZoomSection this[int index] { get; }
```

### Ejemplos

El ejemplo demuestra cómo obtener un elemento de la sección de resumen de zoom por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection zoomSection = collection[1];
}
```

### Véase también

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../isummaryzoomsectioncollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->