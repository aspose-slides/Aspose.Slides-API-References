---
title: AddAutoShape()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างอัตโนมัติรูปแบบใหม่พร้อมการฟอร์แมตเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปทรง.
type: docs
weight: 352
url: /th/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) เมธอด

สร้างอัตโนมัติรูปแบบใหม่พร้อมการฟอร์แมตเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปทรง.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของอัตโนมัติรูปแบบที่ต้องการเพิ่ม. |
| x | **float** | พิกัด x ของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| y | **float** | พิกัด y ของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของกรอบรูปทรง, หน่วยเป็นพอยต์. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ที่สร้างใหม่ [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) เมธอด

สร้างอัตโนมัติรูปแบบใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปทรง, โดยอาจเริ่มต้นด้วยการฟอร์แมตเทมเพลตเริ่มต้น.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของอัตโนมัติรูปแบบที่ต้องการเพิ่ม. |
| x | **float** | พิกัด x ของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| y | **float** | พิกัด y ของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของกรอบรูปทรง, หน่วยเป็นพอยต์. |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (สไตล์ง่าย, ข้อความกึ่งกลาง, และชื่อที่ไม่ว่าง) กับรูปทรงใหม่; false เพื่อสร้างรูปทรงโดยตั้งค่าทุกคุณสมบัติเป็นค่าดีฟอลต์. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ที่สร้างใหม่ [IAutoShape](../../iautoshape/).

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)