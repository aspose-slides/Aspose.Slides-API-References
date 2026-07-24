---
title: AddZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Shape-Collection hinzu.
type: docs
weight: 105
url: /de/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) Methode


Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Shape-Collection hinzu.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Zoom-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Rahmens, in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Der von dem Zoom-Rahmen referenzierte [ISlide](../../islide/); muss zu dieser Präsentation gehören. |

### Rückgabewert

Der neu erstellte [IZoomFrame](../../izoomframe/).

## Hinweise


Dieses Beispiel zeigt das Hinzufügen eines Zoom-Objekts zum Ende einer Sammlung (es wird angenommen, dass sich mindestens zwei Folien in der Präsentation "Presentation.pptx" befinden): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) Methode


Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Shape-Collection hinzu.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Zoom-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Rahmens, in Punkten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Der von dem Zoom-Rahmen referenzierte [ISlide](../../islide/); muss zu dieser Präsentation gehören. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das Bild für die referenzierte Folie [IPPImage](../../ippimage/). |

### Rückgabewert

Der neu erstellte [IZoomFrame](../../izoomframe/).

## Hinweise


Dieses Beispiel zeigt das Hinzufügen eines Zoom-Objekts zum Ende einer Sammlung (es wird angenommen, dass sich mindestens zwei Folien in der Präsentation "Presentation.pptx" befinden): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IZoomFrame](../../izoomframe/)
* Klasse [ISlide](../../islide/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)