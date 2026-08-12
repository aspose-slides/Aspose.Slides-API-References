---
title: Contains()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบันหรือไม่
type: docs
weight: 248
url: /th/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const method

กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบันหรือไม่

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | int | พิกัด X ของจุดที่ต้องตรวจสอบ |
| y | int | พิกัด Y ของจุดที่ต้องตรวจสอบ |

### ค่าที่ส่งคืน

True หากจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน, มิฉะนั้น - false

## Rectangle::Contains(const Point\&) const method

กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบันหรือไม่

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | const [Point](../../point/)\& | จุดที่ต้องตรวจสอบ |

### ค่าที่ส่งคืน

True หากจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน, มิฉะนั้น - false

## Rectangle::Contains(const Rectangle\&) const method

กำหนดว่าสี่เหลี่ยมที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบันหรือไม่

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | สี่เหลี่ยมที่ต้องตรวจสอบ |

### ค่าที่ส่งคืน

True หากสี่เหลี่ยมที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [Rectangle](../)
* คลาส [Point](../../point/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)