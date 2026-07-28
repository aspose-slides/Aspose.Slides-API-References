---
title: InsertPictureFrame()
second_title: Aspose.Slides a C++ API-referencia
description: Új képkeretet hoz létre a megadott képpel, és a megadott indexnél beszúrja a formagyűjteménybe.
type: docs
weight: 417
url: /hu/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metódus

Új képkeretet hoz létre a megadott képpel, és beszúrja a formagyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the picture frame. |
| shapeType | [ShapeType](../../shapetype/) | Megadja a [ShapeType](../../shapetype/)-ben található alakzat típusát, kivéve mindenféle vonalat:

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
| x | **float** | A képkeret x-koordinátája pontban. |
| y | **float** | A képkeret y-koordinátája pontban. |
| width | **float** | A képkeret szélessége pontban. |
| height | **float** | A képkeret magassága pontban. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A [IPPImage](../../ippimage/) a képkeretben megjelenítendő. |

### Visszatérési érték

Az újonnan létrehozott [IPictureFrame](../../ipictureframe/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPictureFrame](../../ipictureframe/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [IShapeCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)