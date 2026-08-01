---
title: InsertZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Zoom frame en voegt het in de vormverzameling in op de opgegeven index.
type: docs
weight: 105
url: /nl/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

Maakt een nieuw Zoom frame en voegt het in de vormverzameling in op de opgegeven index.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het Zoom frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom frame, in punten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar verwezen wordt door het Zoom frame. |

### Retourwaarde

De nieuw aangemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen

Dit voorbeeld demonstreert het maken en invoegen van een Zoom object op de opgegeven index van een collectie (veronderstel dat er ten minste twee dia's in de "Presentation.pptx" presentatie staan):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Maakt een nieuw Zoom frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in op de opgegeven index.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het Zoom frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom frame, in punten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar verwezen wordt door het Zoom frame. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De afbeelding voor de refererende dia [IPPImage](../../ippimage/). |

### Retourwaarde

De nieuw aangemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen

Dit voorbeeld demonstreert het maken en invoegen van een Zoom object op de opgegeven index van een collectie (veronderstel dat er ten minste twee dia's in de "Presentation.pptx" presentatie staan):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IZoomFrame](../../izoomframe/)
* Klasse [ISlide](../../islide/)
* Klasse [IShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)