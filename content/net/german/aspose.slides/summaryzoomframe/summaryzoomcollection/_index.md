---
title: SummaryZoomCollection
second_title: Aspose.Slides für .NET API-Referenz
description: Erhält ISummaryZoomSectionCollectionaspose.slides/isummaryzoomsectioncollection für das Summary Zoom Frame-Objekt.
type: docs
weight: 20
url: /de/aspose.slides/summaryzoomframe/summaryzoomcollection/
---

## SummaryZoomFrame.SummaryZoomCollection-Eigenschaft

Erhält [`ISummaryZoomSectionCollection`](../../isummaryzoomsectioncollection) für das Summary Zoom Frame-Objekt.

```csharp
public ISummaryZoomSectionCollection SummaryZoomCollection { get; }
```

### Beispiele

Das Beispiel demonstriert das Abrufen des Summary Zoom Section-Elements nach Index:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
}
```

### Siehe auch

* Schnittstelle [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* Klasse [SummaryZoomFrame](../../summaryzoomframe)
* Namespace [Aspose.Slides](../../summaryzoomframe)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->