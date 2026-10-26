---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Summary Zoom frame und fügt es am Ende der Shape Collection hinzu.
type: docs
weight: 144
url: /de/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) Methode

Erstellt ein neues Summary Zoom frame und fügt es am Ende der shape collection hinzu.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Summary Zoom frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom frames, in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom frames, in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom frames, in Punkten. |

### Rückgabewert

Das neu erstellte [ISummaryZoomFrame](../../isummaryzoomframe/).

## Bemerkungen

Diese Methode erstellt ein Summary Zoom frame, das Zusammenfassungs-Links für alle Abschnitte in der Präsentation aggregiert. 

Dieses Beispiel zeigt das Hinzufügen eines Summary Zoom-Objekts zum Ende einer Collection (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)