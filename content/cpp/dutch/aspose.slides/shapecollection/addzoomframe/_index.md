---
title: AddZoomFrame()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 105
url: /nl/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) methode


Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in points. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in points. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in points. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar het Zoom-frame verwijst; moet tot deze presentatie behoren. |

### Retourwaarde

Het nieuw aangemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen


Dit voorbeeld demonstreert het toevoegen van een Zoom-object aan het einde van een collectie (ga ervan uit dat er minstens twee dia's zijn in de "Presentation.pptx" presentatie): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) methode


Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in points. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in points. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in points. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar het Zoom-frame verwijst; moet tot deze presentatie behoren. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De afbeelding voor de verwijzende dia [IPPImage](../../ippimage/). |

### Retourwaarde

Het nieuw aangemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen


Dit voorbeeld demonstreert het toevoegen van een Zoom-object aan het einde van een collectie (ga ervan uit dat er minstens twee dia's zijn in de "Presentation.pptx" presentatie): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IZoomFrame](../../izoomframe/)
* Klasse [ISlide](../../islide/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)