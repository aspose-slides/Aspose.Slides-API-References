---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Summary Zoom-Frame und fügt ihn am Ende der Shape-Sammlung hinzu.
type: docs
weight: 157
url: /de/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) Methode

Erstellt einen neuen Summary Zoom-Frame und fügt ihn am Ende der Shape-Sammlung hinzu.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Summary Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom-Frames, in Punkten. |

### Rückgabewert

Das neu erstellte [ISummaryZoomFrame](../../isummaryzoomframe/).
## Hinweise


Diese Methode erstellt ein neues Summary Zoom und legt für alle Abschnitte in dieser Präsentation eine Sammlung von Objekten darin ab.

Dieses Beispiel zeigt, wie ein Summary Zoom-Objekt am Ende einer Sammlung hinzugefügt wird (nehmen Sie an, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)