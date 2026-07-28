---
title: InsertPictureFrame()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új képkeretet a megadott képpel, és a megadott indexnél beilleszti az alakgyűjteménybe.
type: docs
weight: 456
url: /hu/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metódus

Létrehoz egy új képkeretet a megadott képpel, és a megadott indexnél beilleszti az alakgyűjteménybe.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulláralapú index, ahol a képkeretet be kell illeszteni. |
| shapeType | [ShapeType](../../shapetype/) | Megadja a [ShapeType](../../shapetype/)-ban található alak típusát, kivéve mindenféle vonalat:

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

* Enumeráció [ShapeType](../../shapetype/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IPictureFrame](../../ipictureframe/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)