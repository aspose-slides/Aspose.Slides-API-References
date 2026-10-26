---
title: AddSectionZoomFrame()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový Section Zoom rámec a přidá jej na konec kolekce tvarů.
type: docs
weight: 131
url: /cs/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metoda

Vytvoří nový [Section](../../section/) Zoom rámec a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového [Section](../../section/) Zoom rámce, v bodech. |
| y | **float** | Y-souřadnice nového [Section](../../section/) Zoom rámce, v bodech. |
| width | **float** | Šířka nového [Section](../../section/) Zoom rámce, v bodech. |
| height | **float** | Výška nového [Section](../../section/) Zoom rámce, v bodech. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odkazovaný [Section](../../section/) Zoom rámcem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

### Návratová hodnota

Nově vytvořený [ISectionZoomFrame](../../isectionzoomframe/).

## Poznámky

Tento příklad ukazuje, jak přidat objekt [Section](../../section/) Zoom na konec kolekce (předpokládejte, že v prezentaci „Presentation.pptx“ existují alespoň dvě sekce):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda

Vytvoří nový [Section](../../section/) Zoom rámec s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového [Section](../../section/) Zoom rámce, v bodech. |
| y | **float** | Y-souřadnice nového [Section](../../section/) Zoom rámce, v bodech. |
| width | **float** | Šířka nového [Section](../../section/) Zoom rámce, v bodech. |
| height | **float** | Výška nového [Section](../../section/) Zoom rámce, v bodech. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odkazovaný [Section](../../section/) Zoom rámcem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) zobrazený v [Section](../../section/) Zoom rámci. |

### Návratová hodnota

Nově vytvořený [ISectionZoomFrame](../../isectionzoomframe/).

## Poznámky

Tento příklad ukazuje, jak přidat objekt [Section](../../section/) Zoom na konec kolekce (předpokládejte, že v prezentaci „Presentation.pptx“ existují alespoň dvě sekce):
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
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)