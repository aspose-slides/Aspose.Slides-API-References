---
title: Item
second_title: Aspose.Slides für .NET API-Referenz
description: Erhält das Element am angegebenen Index. Nur lesender ISummaryZoomSectionaspose.slides/isummaryzoomsection.
type: docs
weight: 10
url: /de/aspose.slides/isummaryzoomsectioncollection/item/
---

## ISummaryZoomSectionCollection-Indexer

Erhält das Element am angegebenen Index. Nur lesender [`ISummaryZoomSection`](../../isummaryzoomsection).

```csharp
public ISummaryZoomSection this[int index] { get; }
```

### Beispiele

Das Beispiel zeigt, wie man das Summary Zoom Section-Element nach Index erhält:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection zoomSection = collection[1];
}
```

### Siehe auch

* Interface [ISummaryZoomSection](../../isummaryzoomsection)
* Interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* Namespace [Aspose.Slides](../../isummaryzoomsectioncollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->