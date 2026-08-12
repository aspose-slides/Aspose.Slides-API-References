---
title: InsertAutoShape()
second_title: Aspose.Slides สำหรับ C++ คู่มืออ้างอิง API
description: สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ โดยใช้การจัดรูปแบบเทมเพลตเริ่มต้น
type: docs
weight: 378
url: /th/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) เมธอด

สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ โดยใช้การจัดรูปแบบเทมเพลตเริ่มต้น

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีศูนย์ฐานที่ใช้ในการแทรกรูปร่างอัตโนมัติใหม่ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปร่างอัตโนมัติที่ต้องการแทรก |
| x | **float** | พิกัด x ของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมของรูปร่าง, หน่วยเป็นจุด |

### ค่าที่ส่งกลับ

[IAutoShape](../../iautoshape/) ที่สร้างใหม่

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) เมธอด

สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ โดยอาจกำหนดค่าเริ่มต้นด้วยสไตล์เทมเพลตเริ่มต้น

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีศูนย์ฐานที่ใช้ในการแทรกรูปร่างอัตโนมัติ |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) ของรูปร่างอัตโนมัติที่ต้องการแทรก |
| x | **float** | พิกัด x ของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมของรูปร่าง, หน่วยเป็นจุด |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (รวมถึงชื่อที่ไม่ว่างเปล่า, สไตล์ง่าย, และข้อความตรงกลาง); false เพื่อสร้างรูปร่างโดยตั้งค่าคุณสมบัติทั้งหมดเป็นค่าเริ่มต้น |

### ค่าที่ส่งกลับ

[IAutoShape](../../iautoshape/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)