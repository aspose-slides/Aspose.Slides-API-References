---
title: Clear
second_title: Aspose.Slides für .NET-API-Referenz
description: Entfernt alle SummaryZoomSectionObjekte aus der Sammlung.
type: docs
weight: 60
url: /de/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection.Clear method

Entfernt alle SummaryZoomSection-Objekte aus der Sammlung.

```csharp
public void Clear()
```

### Beispiele

Das Beispiel zeigt das Abrufen des Elements Summary Zoom Section nach Index:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.Clear();
}
```

### Siehe auch

* class [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* namensraum [Aspose.Slides](../../summaryzoomsectioncollection)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
