---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Summary Zoom Frame und fügt ihn in die Shape-Sammlung an dem angegebenen Index ein.
type: docs
weight: 157
url: /de/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) Methode

Erstellt einen neuen Summary Zoom-Frame und fügt ihn in die Shape-Sammlung an dem angegebenen Index ein.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Summary Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Summary Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom-Frames in Punkten. |

### Rückgabewert

Der neu erstellte [ISummaryZoomFrame](../../isummaryzoomframe/).

## Hinweise

Diese Methode erstellt einen Summary Zoom-Frame, der Zusammenfassungslinks für alle Abschnitte der Präsentation aggregiert.

Dieses Beispiel demonstriert das Erstellen und Einfügen eines Summary Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)