---
title: AddZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Zoom frame aan en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 92
url: /nl/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) methode


Creëert een nieuwe Zoom frame en voegt deze toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van de nieuwe Zoom frame, in punten. |
| y | **float** | De y-coördinaat van de nieuwe Zoom frame, in punten. |
| width | **float** | De breedte van de nieuwe Zoom frame, in punten. |
| height | **float** | De hoogte van de nieuwe Zoom frame, in punten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar verwezen wordt door de Zoom frame; moet behoren tot deze presentatie. |

### Retourwaarde

De nieuw aangemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen


Dit voorbeeld toont het toevoegen van een Zoom object aan het einde van een collectie (veronderstel dat er ten minste twee slides in de "Presentation.pptx" presentatie zijn): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) methode


Creëert een nieuwe Zoom frame en voegt deze toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van de nieuwe Zoom frame, in punten. |
| y | **float** | De y-coördinaat van de nieuwe Zoom frame, in punten. |
| width | **float** | De breedte van de nieuwe Zoom frame, in punten. |
| height | **float** | De hoogte van de nieuwe Zoom frame, in punten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar verwezen wordt door de Zoom frame; moet behoren tot deze presentatie. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De afbeelding voor de verwijzende slide [IPPImage](../../ippimage/). |

### Retourwaarde

De nieuw aangemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen


Dit voorbeeld toont het toevoegen van een Zoom object aan het einde van een collectie (veronderstel dat er ten minste twee slides in de "Presentation.pptx" presentatie zijn): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)