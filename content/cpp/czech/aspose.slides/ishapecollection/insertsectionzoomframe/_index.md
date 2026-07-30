---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří nový rámec Section Zoom a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 131
url: /cs/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metoda

Vytvoří nový [Section](../../section/) Zoom frame a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit [Section](../../section/) Zoom frame. |
| x | **float** | Souřadnice x nového [Section](../../section/) Zoom frame v bodech. |
| y | **float** | Souřadnice y nového [Section](../../section/) Zoom frame v bodech. |
| width | **float** | Šířka nového [Section](../../section/) Zoom frame v bodech. |
| height | **float** | Výška nového [Section](../../section/) Zoom frame v bodech. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odkazovaný [Section](../../section/) Zoom frame; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

### Návratová hodnota

Nově vytvořený [ISectionZoomFrame](../../isectionzoomframe/).

## Poznámky

Tento příklad ukazuje vytvoření a vložení [Section](../../section/) Zoom objektu na zadaný index v kolekci (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda

Vytvoří nový [Section](../../section/) Zoom frame s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit [Section](../../section/) Zoom frame. |
| x | **float** | Souřadnice x nového [Section](../../section/) Zoom frame v bodech. |
| y | **float** | Souřadnice y nového [Section](../../section/) Zoom frame v bodech. |
| width | **float** | Šířka nového [Section](../../section/) Zoom frame v bodech. |
| height | **float** | Výška nového [Section](../../section/) Zoom frame v bodech. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odkazovaný [Section](../../section/) Zoom frame; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obrázek, který se má zobrazit v [Section](../../section/) Zoom frame. |

### Návratová hodnota

Nově vytvořený [ISectionZoomFrame](../../isectionzoomframe/).

## Poznámky

Tento příklad ukazuje vytvoření a vložení [Section](../../section/) Zoom objektu na zadaný index v kolekci (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)