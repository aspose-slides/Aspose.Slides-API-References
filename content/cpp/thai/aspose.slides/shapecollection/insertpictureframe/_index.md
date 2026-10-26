---
title: InsertPictureFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งดัชนีที่กำหนด
type: docs
weight: 456
url: /th/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) เมธอด


สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งดัชนีที่กำหนด

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีแบบศูนย์ฐานที่ต้องการแทรกกรอบรูปภาพ |
| shapeType | [ShapeType](../../shapetype/) | ระบุประเภทของรูปทรงที่อยู่ใน [ShapeType](../../shapetype/) ยกเว้นประเภทเส้นทั้งหมด:

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
| x | **float** | พิกัด x ของกรอบรูปภาพ (หน่วย points) |
| y | **float** | พิกัด y ของกรอบรูปภาพ (หน่วย points) |
| width | **float** | ความกว้างของกรอบรูปภาพ (หน่วย points) |
| height | **float** | ความสูงของกรอบรูปภาพ (หน่วย points) |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) ที่จะแสดงในกรอบรูปภาพ |

### Return Value

[IPictureFrame](../../ipictureframe/) ที่สร้างขึ้นใหม่

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)