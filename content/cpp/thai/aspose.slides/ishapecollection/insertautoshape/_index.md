---
title: InsertAutoShape()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: สร้างรูปอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปที่ตำแหน่งที่ระบุ โดยใช้การจัดรูปแบบแม่แบบเริ่มต้น
type: docs
weight: 339
url: /th/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) เมธอด

สร้างรูปอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปที่ตำแหน่งที่ระบุ โดยใช้รูปแบบแม่แบบเริ่มต้น

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้เพื่อแทรกรูปอัตโนมัติใหม่ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปอัตโนมัติที่จะใส่ |
| x | **float** | พิกัด x ของกรอบรูป, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบรูป, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบรูป, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบรูป, หน่วยเป็นจุด |

### ค่าที่ส่งคืน

[IAutoShape](../../iautoshape/) ที่สร้างใหม่.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) เมธอด

สร้างรูปอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปที่ตำแหน่งที่ระบุ โดยอาจเริ่มต้นด้วยการใช้สไตล์แม่แบบเริ่มต้น

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้เพื่อแทรกรูปอัตโนมัติ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปอัตโนมัติที่จะใส่ |
| x | **float** | พิกัด x ของกรอบรูป, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบรูป, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบรูป, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบรูป, หน่วยเป็นจุด |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์แม่แบบเริ่มต้น (รวมถึงชื่อที่ไม่ว่างเปล่า, สไตล์แบบง่าย, และข้อความอยู่กึ่งกลาง); false เพื่อสร้างรูปโดยกำหนดคุณสมบัติทั้งหมดเป็นค่าเริ่มต้น |

### ค่าที่ส่งคืน

[IAutoShape](../../iautoshape/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)