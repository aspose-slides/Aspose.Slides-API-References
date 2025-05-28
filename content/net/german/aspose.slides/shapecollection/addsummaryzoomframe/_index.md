---
title: AddSummaryZoomFrame
second_title: Aspose.Slides für .NET API Referenz
description: Fügt ein neues Summary Zoom-Objekt am Ende einer Sammlung hinzu.
type: docs
weight: 190
url: /de/aspose.slides/shapecollection/addsummaryzoomframe/
---

## ShapeCollection.AddSummaryZoomFrame-Methode

Fügt ein neues Summary Zoom-Objekt am Ende einer Sammlung hinzu.

```csharp
public ISummaryZoomFrame AddSummaryZoomFrame(float x, float y, float width, float height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen Section Zoom-Rahmens Single. |
| y | Single | Y-Koordinate eines neuen Section Zoom-Rahmens Single. |
| width | Single | Breite eines neuen Section Zoom-Rahmens Single. |
| height | Single | Höhe eines neuen Section Zoom-Rahmens Single. |

### Rückgabewert

Erstellt das Summary Zoom-Objekt [`ISummaryZoomFrame`](../../isummaryzoomframe).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Es gibt keine Abschnitte in der Präsentation oder die Zielfolie gehört zu keinem Abschnitt. |

### Bemerkungen

Diese Methode erstellt ein neues Summary Zoom und fügt ihm eine Sammlung von Objekten für alle Abschnitte in dieser Präsentation hinzu.

### Beispiele

Dieses Beispiel zeigt, wie ein Summary Zoom-Objekt am Ende einer Sammlung hinzugefügt wird (nehmen Sie an, dass es in der Präsentation "Presentation.pptx" mindestens zwei Abschnitte gibt):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.AddSummaryZoomFrame(150, 20, 500, 250);
}
```

### Siehe auch

* Schnittstelle [ISummaryZoomFrame](../../isummaryzoomframe)
* Klasse [ShapeCollection](../../shapecollection)
* Namespace [Aspose.Slides](../../shapecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->