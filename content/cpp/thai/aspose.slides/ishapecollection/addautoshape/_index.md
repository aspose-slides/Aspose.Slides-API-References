---
title: AddAutoShape()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างรูปร่างอัตโนมัติใหม่พร้อมรูปแบบเริ่มต้นและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 313
url: /th/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) เมธอด

สร้างรูปร่างอัตโนมัติใหม่พร้อมรูปแบบเริ่มต้นและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\u2019s frame, in points. |
| width | **float** | The width of the shape\u2019s frame, in points. |
| height | **float** | The height of the shape\u2019s frame, in points. |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ที่สร้างใหม่ [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) เมธอด

สร้างรูปร่างอัตโนมัติใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่างโดยอาจกำหนดค่าเริ่มต้นด้วยรูปแบบเทมเพลตเริ่มต้น.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\u2019s frame, in points. |
| width | **float** | The width of the shape\u2019s frame, in points. |
| height | **float** | The height of the shape\u2019s frame, in points. |
| createFromTemplate | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (สไตล์ง่าย, ข้อความตรงกลาง, และชื่อไม่ว่าง) กับรูปร่างใหม่; false เพื่อสร้างรูปร่างโดยตั้งค่าทุกคุณสมบัติเป็นค่าดีฟอลต์. |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ที่สร้างใหม่ [IAutoShape](../../iautoshape/).

## ดูเพิ่มเติม

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)