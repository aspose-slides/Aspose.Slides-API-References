---
title: AddPictureFrame()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy új képkeretet a megadott képpel, és hozzáadja a formai gyűjtemény végéhez.
type: docs
weight: 404
url: /hu/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metódus


Létrehoz egy új képkeretet a megadott képpel, és hozzáadja a formai gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Megadja a [ShapeType](../../shapetype/)-ban található alakzat típusát, kivéve mindenféle vonalat:

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
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)