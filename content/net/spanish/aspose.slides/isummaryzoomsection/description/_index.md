---
title: Description
second_title: Aspose.Sildes for .NET API Reference
description: Devuelve la descripción de texto del objeto Summary Zoom Section.
type: docs
weight: 20
url: /es/aspose.slides/isummaryzoomsection/description/
---

## ISummaryZoomSection.Description property

Devuelve la descripción de texto del objeto Summary Zoom Section.

```csharp
public string Description { get; set; }
```

### Examples

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomSection zoomSection = zoomFrame.SummaryZoomCollection[1];
    zoomSection.Description = "Description";
}
```

### See Also

* interface [ISummaryZoomSection](../../isummaryzoomsection)
* namespace [Aspose.Slides](../../isummaryzoomsection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->