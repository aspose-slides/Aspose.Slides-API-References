---
title: Description
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve la descripción de texto del objeto Sección de zoom de resumen.
type: docs
weight: 20
url: /es/net/aspose.slides/isummaryzoomsection/description/
---
## ISummaryZoomSection.Description property

Devuelve la descripción de texto del objeto Sección de zoom de resumen.

```csharp
public string Description { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomSection zoomSection = zoomFrame.SummaryZoomCollection[1];
    zoomSection.Description = "Description";
}
```

### Ver también

* interface [ISummaryZoomSection](../../isummaryzoomsection)
* espacio de nombres [Aspose.Slides](../../isummaryzoomsection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->