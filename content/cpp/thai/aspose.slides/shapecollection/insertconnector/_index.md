---
title: InsertConnector()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างรูปร่างตัวเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ พร้อมใช้สไตล์เทมเพลตเริ่มต้น.
type: docs
weight: 430
url: /th/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) เมธodb

สร้างรูปร่างตัวเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ พร้อมใช้สไตล์เทมเพลตเริ่มต้น.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างตัวเชื่อมต่อ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปร่างตัวเชื่อมต่อที่จะแทรก |
| x | **float** | ค่าพิกัด x ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| y | **float** | ค่าพิกัด y ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| width | **float** | ความกว้างของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| height | **float** | ความสูงของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |

### ค่าที่ส่งกลับ

[IConnector](../../iconnector/) ที่สร้างใหม่

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) เมธodb

สร้างรูปร่างตัวเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ โดยอาจใช้สไตล์เทมเพลตเริ่มต้น.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างตัวเชื่อมต่อ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปร่างตัวเชื่อมต่อที่จะแทรก |
| x | **float** | ค่าพิกัด x ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| y | **float** | ค่าพิกัด y ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| width | **float** | ความกว้างของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| height | **float** | ความสูงของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นพ้อยท์ |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่างเปล่า, สไตล์แบบง่าย); false เพื่อสร้างตัวเชื่อมต่อโดยใช้ค่าคุณสมบัติเริ่มต้น |

### ค่าที่ส่งกลับ

[IConnector](../../iconnector/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IConnector](../../iconnector/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)