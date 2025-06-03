---
title: Clear
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina todos los objetos SummaryZoomSection de la colección.
type: docs
weight: 60
url: /es/aspose.slides/summaryzoomsectioncollection/clear/
---

## Método SummaryZoomSectionCollection.Clear

Elimina todos los objetos SummaryZoomSection de la colección.

```csharp
public void Clear()
```

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de la sección de zoom resumido por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.Clear();
}
```

### Véase También

* clase [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../summaryzoomsectioncollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->