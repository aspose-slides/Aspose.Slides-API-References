---
title: Title
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve el título de texto del objeto Summary Zoom Section.
type: docs
weight: 20
url: /es/aspose.slides/summaryzoomsection/title/
---

## Propiedad SummaryZoomSection.Title

Devuelve el título de texto del objeto Summary Zoom Section.

```csharp
public string Title { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomSection zoomSection = zoomFrame.SummaryZoomCollection[1];
    zoomSection.Title = "Title";
}
```

### Ver También

* clase [SummaryZoomSection](../../summaryzoomsection)
* espacio de nombres [Aspose.Slides](../../summaryzoomsection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
