---
title: InsertPictureFrame()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 456
url: /cs/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit rámeček obrázku. |
| shapeType | [ShapeType](../../shapetype/) | Určuje typ tvaru obsažený v [ShapeType](../../shapetype/), kromě všech druhů čar:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Souřadnice x rámečku obrázku v bodech. |
| y | **float** | Souřadnice y rámečku obrázku v bodech. |
| width | **float** | Šířka rámečku obrázku v bodech. |
| height | **float** | Výška rámečku obrázku v bodech. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) k zobrazení v rámečku obrázku. |

### Návratová hodnota

Nově vytvořený [IPictureFrame](../../ipictureframe/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)