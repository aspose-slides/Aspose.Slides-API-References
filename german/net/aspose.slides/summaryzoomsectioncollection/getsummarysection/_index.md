---
title: GetSummarySection
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt zusammenfassendes ZoomAbschnittselement für den angegebenen Abschnitt zurück.
type: docs
weight: 90
url: /de/net/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection.GetSummarySection method

Gibt zusammenfassendes Zoom-Abschnittselement für den angegebenen Abschnitt zurück.

```csharp
public ISummaryZoomSection GetSummarySection(ISection section)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | ISection | Abschnitt zu finden[`ISection`](../../isection) |

### Rückgabewert

[`ISummaryZoomSection`](../../isummaryzoomsection) oder null, wenn die Sammlung kein Element für den Abschnitt enthält.

### Beispiele

Das Beispiel zeigt das Abrufen des Elements Summary Zoom Section nach Index:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection selectedObject = collection.GetSummarySection(pres.Sections[2]);
}
```

### Siehe auch

* interface [ISummaryZoomSection](../../isummaryzoomsection)
* interface [ISection](../../isection)
* class [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* namensraum [Aspose.Slides](../../summaryzoomsectioncollection)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->