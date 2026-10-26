---
title: AddPictureFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างเฟรมรูปภาพใหม่ที่มีภาพที่ระบุและเพิ่มเข้าไปยังส่วนท้ายของคอลเลกชันรูปทรง.
type: docs
weight: 443
url: /th/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method


สร้างเฟรมรูปภาพใหม่ที่มีภาพที่ระบุและเพิ่มเข้าไปยังส่วนท้ายของคอลเลกชันรูปทรง.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ระบุประเภทของรูปทรงที่อยู่ใน [ShapeType](../../shapetype/) ยกเว้นรูปแบบเส้นทั้งหมด:

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
| x | **float** | พิกัด x ของเฟรมรูปภาพ (หน่วยเป็นจุด). |
| y | **float** | พิกัด y ของเฟรมรูปภาพ (หน่วยเป็นจุด). |
| width | **float** | ความกว้างของเฟรมรูปภาพ (หน่วยเป็นจุด). |
| height | **float** | ความสูงของเฟรมรูปภาพ (หน่วยเป็นจุด). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) ที่จะแสดงในเฟรมรูปภาพ. |

### ค่าที่ส่งกลับ

[IPictureFrame](../../ipictureframe/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)