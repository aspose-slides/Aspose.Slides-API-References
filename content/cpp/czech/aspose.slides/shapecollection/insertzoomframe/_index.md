---
title: InsertZoomFrame()
second_title: Aspose.Slides pro C++ API
description: Vytvoří nový Zoom frame a vloží jej do kolekce tvarů na určeném indexu.
type: docs
weight: 118
url: /cs/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) metoda

Vytvoří nový Zoom frame a vloží jej do kolekce tvarů na určeném indexu.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově založený index, na kterém se má vložit Zoom frame. |
| x | **float** | X-souřadnice nového Zoom frame v bodech. |
| y | **float** | Y-souřadnice nového Zoom frame v bodech. |
| width | **float** | Šířka nového Zoom frame v bodech. |
| height | **float** | Výška nového Zoom frame v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odkazovaný Zoom frame. |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky

Tento příklad ukazuje vytvoření a vložení objektu Zoom na určený index v kolekci (předpokládejme, že v prezentaci \"Presentation.pptx\" jsou alespoň dva snímky): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metoda

Vytvoří nový Zoom frame s předdefinovaným obrázkem a vloží jej do kolekce tvarů na určeném indexu.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově založený index, na kterém se má vložit Zoom frame. |
| x | **float** | X-souřadnice nového Zoom frame v bodech. |
| y | **float** | Y-souřadnice nového Zoom frame v bodech. |
| width | **float** | Šířka nového Zoom frame v bodech. |
| height | **float** | Výška nového Zoom frame v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odkazovaný Zoom frame. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obrázek pro odkazovaný snímek [IPPImage](../../ippimage/). |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky

Tento příklad ukazuje vytvoření a vložení objektu Zoom na určený index v kolekci (předpokládejme, že v prezentaci \"Presentation.pptx\" jsou alespoň dva snímky): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IZoomFrame](../../izoomframe/)
* Třída [ISlide](../../islide/)
* Třída [ShapeCollection](../)
* Třída [IPPImage](../../ippimage/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)