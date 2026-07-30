---
title: AddPictureFrame()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů.
type: docs
weight: 404
url: /cs/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metoda

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Určuje typ tvaru obsažený v [ShapeType](../../shapetype/), s výjimkou všech druhů čar:

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
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)