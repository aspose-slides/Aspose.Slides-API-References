---
title: AddPictureFrame()
second_title: Aspose.Slides C++ API referencia
description: Új képkockát hoz létre, amely a megadott képet tartalmazza, és a forma gyűjtemény végéhez adja hozzá.
type: docs
weight: 443
url: /hu/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metódus

Új képkockát hoz létre, amely a megadott képet tartalmazza, és a forma gyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Megadja a [ShapeType](../../shapetype/)-ban lévő alakzat típusát, kivéve az összes vonal típusát:

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
| x | **float** | A képkocka x koordinátája pontban. |
| y | **float** | A képkocka y koordinátája pontban. |
| width | **float** | A képkocka szélessége pontban. |
| height | **float** | A képkocka magassága pontban. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A képkockában megjelenítendő [IPPImage](../../ippimage/). |

### Visszatérési érték

Az újonnan létrehozott [IPictureFrame](../../ipictureframe/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPictureFrame](../../ipictureframe/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [ShapeCollection](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)