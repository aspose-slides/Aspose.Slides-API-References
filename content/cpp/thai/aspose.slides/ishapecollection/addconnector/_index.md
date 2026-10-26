---
title: AddConnector()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างรูปแบบเชื่อมต่อใหม่พร้อมการจัดรูปแบบแม่แบบเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปแบบ.
type: docs
weight: 378
url: /th/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) เมธอด

สร้างรูปแบบเชื่อมต่อใหม่พร้อมการจัดรูปแบบแม่แบบเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปแบบ.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) ของรูปแบบเชื่อมต่อที่จะเพิ่ม. |
| x | **float** | พิกัด x ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |

### ค่าที่ส่งกลับ

[IConnector](../../iconnector/) ที่สร้างใหม่.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) เมธอด

สร้างรูปแบบเชื่อมต่อใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปแบบ, โดยอาจใช้การจัดรูปแบบแม่แบบเริ่มต้น.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) ของรูปแบบเชื่อมต่อที่จะสร้าง. |
| x | **float** | พิกัด x ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด. |
| createFromTemplate | **bool** | True เพื่อใช้การจัดรูปแบบแม่แบบเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); false เพื่อสร้างตัวเชื่อมต่อด้วยค่าคุณสมบัติเพิ่มต้น. |

### ค่าที่ส่งกลับ

[IConnector](../../iconnector/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IConnector](../../iconnector/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)