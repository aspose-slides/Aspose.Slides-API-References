---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Summary Zoom frame und fügt es in die shape collection an dem angegebenen Index ein.
type: docs
weight: 170
url: /de/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) Methode

Erstellt ein neues Summary Zoom-frame und fügt es in die Shape-Collection an dem angegebenen Index ein.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Summary Zoom frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Summary Zoom frame in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom frame in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom frame in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom frame in Punkten. |

### Rückgabewert

Das neu erstellte [ISummaryZoomFrame](../../isummaryzoomframe/).

## Hinweise

Diese Methode erstellt ein Summary Zoom frame, das Zusammenfassungs-Links für alle Abschnitte der Präsentation aggregiert.

Dieses Beispiel demonstriert das Erstellen und Einfügen eines Summary Zoom-Objekts an dem angegebenen Index einer Collection (es wird angenommen, dass die "Presentation.pptx"-Präsentation mindestens zwei Abschnitte enthält):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)