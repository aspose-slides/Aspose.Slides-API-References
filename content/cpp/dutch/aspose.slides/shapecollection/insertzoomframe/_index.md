---
title: InsertZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Zoom-frame en voegt het toe aan de vormverzameling op de opgegeven index.
type: docs
weight: 118
url: /nl/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) methode

Maakt een nieuw Zoom-frame en voegt het toe aan de vormverzameling op de opgegeven index.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar het Zoom-frame verwijst. |

### Retourwaarde

De nieuw gemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen

Dit voorbeeld toont het maken en invoegen van een Zoom-object op de opgegeven index van een collectie (ga er vanuit dat er minstens twee dia's zijn in de presentatie "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) methode

Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan de vormverzameling op de opgegeven index.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | De [ISlide](../../islide/) waarnaar het Zoom-frame verwijst. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De afbeelding voor de verwijzende dia [IPPImage](../../ippimage/). |

### Retourwaarde

De nieuw gemaakte [IZoomFrame](../../izoomframe/).

## Opmerkingen

Dit voorbeeld toont het maken en invoegen van een Zoom-object op de opgegeven index van een collectie (ga er vanuit dat er minstens twee dia's zijn in de presentatie "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)