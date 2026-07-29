---
title: AddPictureFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.
type: docs
weight: 404
url: /sv/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metod

Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Anger formtypen som finns i [ShapeType](../../shapetype/), förutom alla typer av linjer:

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
| x | **float** | x-koordinaten för bildramen, i punkter. |
| y | **float** | y-koordinaten för bildramen, i punkter. |
| width | **float** | Bredden på bildramen, i punkter. |
| height | **float** | Höjden på bildramen, i punkter. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Den [IPPImage](../../ippimage/) som ska visas i bildramen. |

### Returvärde

Den nyss skapade [IPictureFrame](../../ipictureframe/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPictureFrame](../../ipictureframe/)
* Klass [IPPImage](../../ippimage/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)