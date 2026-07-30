---
title: InsertZoomFrame()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 105
url: /cs/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se vloží Zoom rámec. |
| x | **float** | X-souřadnice nového Zoom rámce v bodech. |
| y | **float** | Y-souřadnice nového Zoom rámce v bodech. |
| width | **float** | Šířka nového Zoom rámce v bodech. |
| height | **float** | Výška nového Zoom rámce v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Objekt [ISlide](../../islide/) odkazovaný Zoom rámcem. |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky

Tento příklad ukazuje vytvoření a vložení objektu Zoom na zadaný index v kolekci (předpokládejte, že v prezentaci „Presentation.pptx“ jsou alespoň dva snímky): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se vloží Zoom rámec. |
| x | **float** | X-souřadnice nového Zoom rámce v bodech. |
| y | **float** | Y-souřadnice nového Zoom rámce v bodech. |
| width | **float** | Šířka nového Zoom rámce v bodech. |
| height | **float** | Výška nového Zoom rámce v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Objekt [ISlide](../../islide/) odkazovaný Zoom rámcem. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obrázek pro odkazovaný snímek [IPPImage](../../ippimage/). |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky

Tento příklad ukazuje vytvoření a vložení objektu Zoom na zadaný index v kolekci (předpokládejte, že v prezentaci „Presentation.pptx“ jsou alespoň dva snímky): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)