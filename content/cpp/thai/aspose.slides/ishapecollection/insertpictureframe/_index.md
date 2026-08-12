---
title: InsertPictureFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างกรอบรูปใหม่ที่มีภาพที่ระบุและแทรกลงในคอลเลกชันรูปทรงตามดัชนีที่ระบุ
type: docs
weight: 417
url: /th/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) เมธอด


สร้างกรอบรูปใหม่ที่มีรูปภาพที่ระบุและแทรกลงใน shape collection ที่ตำแหน่งดัชนีที่ระบุ

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้แทรกกรอบรูป |
| shapeType | [ShapeType](../../shapetype/) | กำหนดประเภทรูปทรงที่อยู่ใน [ShapeType](../../shapetype/) ยกเว้นสำหรับทุกประเภทของเส้น: [ShapeType::Line](../../shapetype/), [ShapeType::StraightConnector1](../../shapetype/), [ShapeType::BentConnector2](../../shapetype/), [ShapeType::BentConnector3](../../shapetype/), [ShapeType::BentConnector4](../../shapetype/), [ShapeType::BentConnector5](../../shapetype/), [ShapeType::CurvedConnector2](../../shapetype/), [ShapeType::CurvedConnector3](../../shapetype/), [ShapeType::CurvedConnector4](../../shapetype/), [ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | พิกัด x ของกรอบรูป หน่วยเป็น points |
| y | **float** | พิกัด y ของกรอบรูป หน่วยเป็น points |
| width | **float** | ความกว้างของกรอบรูป หน่วยเป็น points |
| height | **float** | ความสูงของกรอบรูป หน่วยเป็น points |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) ที่จะแสดงในกรอบรูป |

### ค่าที่คืนกลับ

[IPictureFrame](../../ipictureframe/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)