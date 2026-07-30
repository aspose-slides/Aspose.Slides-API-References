---
title: AddSectionZoomFrame()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový Section Zoom rámeček a přidá jej na konec kolekce tvarů.
type: docs
weight: 118
url: /cs/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metoda


Vytvoří nový [Section](../../section/) Zoom rámeček a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X-souřadnice nového [Section](../../section/) Zoom rámečku, v bodech. |
| y | **float** | Y-souřadnice nového [Section](../../section/) Zoom rámečku, v bodech. |
| width | **float** | Šířka nového [Section](../../section/) Zoom rámečku, v bodech. |
| height | **float** | Výška nového [Section](../../section/) Zoom rámečku, v bodech. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odkazovaný [Section](../../section/) Zoom rámečkem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

### Návratová hodnota

Nově vytvořený [ISectionZoomFrame](../../isectionzoomframe/).

## Poznámky


Tento příklad ukazuje přidání [Section](../../section/) Zoom objektu na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda


Vytvoří nový [Section](../../section/) Zoom rámeček s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X-souřadnice nového [Section](../../section/) Zoom rámečku, v bodech. |
| y | **float** | Y-souřadnice nového [Section](../../section/) Zoom rámečku, v bodech. |
| width | **float** | Šířka nového [Section](../../section/) Zoom rámečku, v bodech. |
| height | **float** | Výška nového [Section](../../section/) Zoom rámečku, v bodech. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odkazovaný [Section](../../section/) Zoom rámečkem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) k zobrazení v [Section](../../section/) Zoom rámečku. |

### Návratová hodnota

Nově vytvořený [ISectionZoomFrame](../../isectionzoomframe/).

## Poznámky


Tento příklad ukazuje přidání [Section](../../section/) Zoom objektu na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)