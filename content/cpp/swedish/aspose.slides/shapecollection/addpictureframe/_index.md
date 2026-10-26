---
title: AddPictureFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.
type: docs
weight: 443
url: /sv/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metod


Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Anger den formtyp som finns i [ShapeType](../../shapetype/), förutom alla typer av linjer:

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

## Se också

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)