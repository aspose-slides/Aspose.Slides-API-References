---
title: Title
second_title: Referencia de API Aspose.Slides para .NET
description: Devuelve el título de texto del objeto Sección de Zoom Resumido.
type: docs
weight: 30
url: /es/aspose.slides/isummaryzoomsection/title/
---

## Propiedad ISummaryZoomSection.Title

Devuelve el título de texto del objeto Sección de Zoom Resumido.

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
    zoomSection.Title = "Título";
}
```

### Ver También

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* espacio de nombres [Aspose.Slides](../../isummaryzoomsection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->