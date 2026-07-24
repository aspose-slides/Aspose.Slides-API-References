---
title: InsertZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Zoom-Rahmen und fügt ihn in die Formsammlung an dem angegebenen Index ein.
type: docs
weight: 118
url: /de/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) Methode

Erstellt einen neuen Zoom-Rahmen und fügt ihn in die Formsammlung an dem angegebenen Index ein.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Zoom-Rahmen eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Das [ISlide](../../islide/) auf das sich der Zoom-Rahmen bezieht. |

### Rückgabewert

Das neu erstellte [IZoomFrame](../../izoomframe/).

## Anmerkungen

Dieses Beispiel demonstriert das Erstellen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass sich mindestens zwei Folien in der Präsentation \"Presentation.pptx\" befinden): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn in die Formsammlung an dem angegebenen Index ein.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Zoom-Rahmen eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Das [ISlide](../../islide/) auf das sich der Zoom-Rahmen bezieht. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das Bild für die referenzierte Folie [IPPImage](../../ippimage/). |

### Rückgabewert

Das neu erstellte [IZoomFrame](../../izoomframe/).

## Anmerkungen

Dieses Beispiel demonstriert das Erstellen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass sich mindestens zwei Folien in der Präsentation \"Presentation.pptx\" befinden): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IZoomFrame](../../izoomframe/)
* Klasse [ISlide](../../islide/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)