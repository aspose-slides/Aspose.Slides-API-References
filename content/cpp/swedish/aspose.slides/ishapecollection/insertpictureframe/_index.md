---
title: InsertPictureFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny bildram som innehåller den angivna bilden och infogar den i shape-samlingen på det angivna indexet.
type: docs
weight: 417
url: /sv/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metod


Skapar en ny bildram som innehåller den angivna bilden och infogar den i shape-samlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där bildramen ska infogas. |
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
| x | **float** | X-koordinaten för bildramen, i punkter. |
| y | **float** | Y-koordinaten för bildramen, i punkter. |
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