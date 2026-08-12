---
title: AddPictureFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างเฟรมรูปภาพใหม่ที่ประกอบด้วยภาพที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 404
url: /th/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) เมธอด

สร้างเฟรมรูปภาพใหม่ที่มีภาพที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ระบุประเภทรูปทรงที่อยู่ใน [ShapeType](../../shapetype/) ยกเว้นทุกประเภทของเส้น:

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
| x | **float** | พิกัด x ของเฟรมรูปภาพ, หน่วยเป็นพอยต์. |
| y | **float** | พิกัด y ของเฟรมรูปภาพ, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของเฟรมรูปภาพ, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของเฟรมรูปภาพ, หน่วยเป็นพอยต์. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) ที่จะแสดงในเฟรมรูปภาพ. |

### ค่าที่ส่งกลับ

[IPictureFrame](../../ipictureframe/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPictureFrame](../../ipictureframe/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)