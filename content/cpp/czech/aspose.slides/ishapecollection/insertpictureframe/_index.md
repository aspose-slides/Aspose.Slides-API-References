---
title: InsertPictureFrame()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na určeném indexu.
type: docs
weight: 417
url: /cs/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na určeném indexu.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit rámeček obrázku. |
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
| x | **float** | X-souřadnice rámečku obrázku v bodech. |
| y | **float** | Y-souřadnice rámečku obrázku v bodech. |
| width | **float** | Šířka rámečku obrázku v bodech. |
| height | **float** | Výška rámečku obrázku v bodech. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) k zobrazení v rámečku obrázku. |

### Návratová hodnota

Nově vytvořený [IPictureFrame](../../ipictureframe/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPictureFrame](../../ipictureframe/)
* Třída [IPPImage](../../ippimage/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)