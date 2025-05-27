---
title: Elemento
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el elemento en el índice especificado. Solo lectura ISummaryZoomSection aspose.slides/isummaryzoomsection.
type: docs
weight: 30
url: /es/aspose.slides/summaryzoomsectioncollection/item/
---

## Índice de SummaryZoomSectionCollection

Obtiene el elemento en el índice especificado. Solo lectura [`ISummaryZoomSection`](../../isummaryzoomsection).

```csharp
public ISummaryZoomSection this[int index] { get; }
```

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de la Sección de Zoom Resumido por índice:

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
* clase [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../summaryzoomsectioncollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->