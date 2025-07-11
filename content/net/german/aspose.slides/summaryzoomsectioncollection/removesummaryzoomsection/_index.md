---
title: RemoveSummaryZoomSection
second_title: Aspose.Slides for .NET API Reference
description: Entfernen Sie das Summary Zoom Section-Objekt aus der Sammlung.
type: docs
weight: 110
url: /de/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---

## SummaryZoomSectionCollection.RemoveSummaryZoomSection method

Entfernen Sie das Summary Zoom Section-Objekt aus der Sammlung.

```csharp
public void RemoveSummaryZoomSection(ISection section)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | ISection | Abschnitt, für den das Element Summary Zoom Section entfernt werden soll [`ISection`](../../isection). |

### Beispiele

Das Beispiel zeigt, wie man das Summary Zoom Section-Element nach Index erhält:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.RemoveSummaryZoomSection(pres.Sections[1]);
}
```

### Siehe auch

* Interface [ISection](../../isection)
* Klasse [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* Namespace [Aspose.Slides](../../summaryzoomsectioncollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
