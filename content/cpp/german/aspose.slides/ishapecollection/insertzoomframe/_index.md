---
title: InsertZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Zoom-Frame und fügt ihn in die Formensammlung an dem angegebenen Index ein.
type: docs
weight: 105
url: /de/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) Methode

Erstellt einen neuen Zoom-Frame und fügt ihn in die Formensammlung an dem angegebenen Index ein.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Der [ISlide](../../islide/), auf den der Zoom-Frame verweist. |

### Rückgabewert

Der neu erstellte [IZoomFrame](../../izoomframe/).

## Hinweise

Dieses Beispiel demonstriert das Erstellen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass die Präsentation \"Presentation.pptx\" mindestens zwei Folien enthält): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen Zoom-Frame mit einem vordefinierten Bild und fügt ihn in die Formensammlung an dem angegebenen Index ein.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Der [ISlide](../../islide/), auf den der Zoom-Frame verweist. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das Bild für die referenzierte Folie [IPPImage](../../ippimage/). |

### Rückgabewert

Der neu erstellte [IZoomFrame](../../izoomframe/).

## Hinweise

Dieses Beispiel demonstriert das Erstellen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass die Präsentation \"Presentation.pptx\" mindestens zwei Folien enthält): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IZoomFrame](../../izoomframe/)
* Klasse [ISlide](../../islide/)
* Klasse [IShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)