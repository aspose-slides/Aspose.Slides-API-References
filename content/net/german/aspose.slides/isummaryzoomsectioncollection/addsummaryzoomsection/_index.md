---
title: AddSummaryZoomSection
second_title: Aspose.Slides für .NET API Referenz
description: Erstellt ein neues Summary Zoom Section-Objekt und fügt es der Sammlung hinzu
type: docs
weight: 20
url: /de/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---

## ISummaryZoomSectionCollection.AddSummaryZoomSection Methode

Erstellt ein neues Summary Zoom Section-Objekt und fügt es der Sammlung hinzu

```csharp
public ISummaryZoomSection AddSummaryZoomSection(ISection section)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | ISection | Abschnitt für ein neues Summary Zoom Section-Element [`ISection`](../../isection) |

### Rückgabewert

Hinzugefügtes [`ISummaryZoomFrame`](../../isummaryzoomframe) Element

### Anmerkungen

Wenn ein Element für diesen Abschnitt bereits in der Sammlung vorhanden ist, wird das vorhandene Element zurückgegeben.

### Beispiel

Das Beispiel demonstriert, wie man ein Summary Zoom Section-Element anhand des Index erhält:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection newZoomSection = collection.AddSummaryZoomSection(pres.Sections[3]);
}
```

### Siehe auch

* Schnittstelle [ISummaryZoomSection](../../isummaryzoomsection)
* Schnittstelle [ISection](../../isection)
* Schnittstelle [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* Namensraum [Aspose.Slides](../../isummaryzoomsectioncollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->