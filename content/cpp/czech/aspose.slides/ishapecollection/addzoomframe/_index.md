---
title: AddZoomFrame()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Vytvoří nový Zoom frame a přidá jej na konec kolekce tvarů.
type: docs
weight: 92
url: /cs/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metoda


Vytvoří nový Zoom frame a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového Zoom frame, v bodech. |
| y | **float** | Y-souřadnice nového Zoom frame, v bodech. |
| width | **float** | Šířka nového Zoom frame, v bodech. |
| height | **float** | Výška nového Zoom frame, v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odkazovaný Zoom frame; musí patřit této prezentaci. |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky


Tento příklad demonstruje přidání objektu Zoom na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metoda


Vytvoří nový Zoom frame a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového Zoom frame, v bodech. |
| y | **float** | Y-souřadnice nového Zoom frame, v bodech. |
| width | **float** | Šířka nového Zoom frame, v bodech. |
| height | **float** | Výška nového Zoom frame, v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odkazovaný Zoom frame; musí patřit této prezentaci. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obrázek pro odkazovaný snímek [IPPImage](../../ippimage/). |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky


Tento příklad demonstruje přidání objektu Zoom na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IZoomFrame](../../izoomframe/)
* Třída [ISlide](../../islide/)
* Třída [IShapeCollection](../)
* Třída [IPPImage](../../ippimage/)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)