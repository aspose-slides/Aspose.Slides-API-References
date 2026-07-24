---
title: AddZoomFrame()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Shape-Collection hinzu.
type: docs
weight: 92
url: /de/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Shape-Collection hinzu.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Das [ISlide](../../islide/) auf das sich der Zoom-Frame bezieht; muss zu dieser Präsentation gehören. |

### Return Value

Der neu erstellte [IZoomFrame](../../izoomframe/).

## Remarks

Dieses Beispiel zeigt das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Folien enthält): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Shape-Collection hinzu.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Das [ISlide](../../islide/) auf das sich der Zoom-Frame bezieht; muss zu dieser Präsentation gehören. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das Bild für die referenzierte Folie [IPPImage](../../ippimage/). |

### Return Value

Der neu erstellte [IZoomFrame](../../izoomframe/).

## Remarks

Dieses Beispiel zeigt das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Folien enthält): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IZoomFrame](../../izoomframe/)
* Klasse [ISlide](../../islide/)
* Klasse [IShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)