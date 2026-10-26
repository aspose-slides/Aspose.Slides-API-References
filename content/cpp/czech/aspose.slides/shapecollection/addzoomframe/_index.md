---
title: AddZoomFrame()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.
type: docs
weight: 105
url: /cs/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metoda

Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového Zoom rámce, v bodech. |
| y | **float** | Y-souřadnice nového Zoom rámce, v bodech. |
| width | **float** | Šířka nového Zoom rámce, v bodech. |
| height | **float** | Výška nového Zoom rámce, v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odkazovaný Zoom rámcem; musí patřit této prezentaci. |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky


Tento příklad ukazuje, jak přidat objekt Zoom na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva slidy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metoda

Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového Zoom rámce, v bodech. |
| y | **float** | Y-souřadnice nového Zoom rámce, v bodech. |
| width | **float** | Šířka nového Zoom rámce, v bodech. |
| height | **float** | Výška nového Zoom rámce, v bodech. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odkazovaný Zoom rámcem; musí patřit této prezentaci. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obrázek pro odkazovaný snímek [IPPImage](../../ippimage/). |

### Návratová hodnota

Nově vytvořený [IZoomFrame](../../izoomframe/).

## Poznámky


Tento příklad ukazuje, jak přidat objekt Zoom na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva slidy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IZoomFrame](../../izoomframe/)
* Třída [ISlide](../../islide/)
* Třída [ShapeCollection](../)
* Třída [IPPImage](../../ippimage/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)