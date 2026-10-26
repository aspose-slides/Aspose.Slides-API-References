---
title: DrawRectangle()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: วาดสี่เหลี่ยมที่กำหนดโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน
type: docs
weight: 287
url: /th/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) เมธอด

วาดสี่เหลี่ยมที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสี่เหลี่ยม |
| x | int | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่วาด |
| y | int | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่วาด |
| width | int | ความกว้างของสี่เหลี่ยมที่วาด |
| height | int | ความสูงของสี่เหลี่ยมที่วาด |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) เมธอด

วาดสี่เหลี่ยมที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสี่เหลี่ยม |
| x | **float** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่วาด |
| y | **float** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่วาด |
| width | **float** | ความกว้างของสี่เหลี่ยมที่วาด |
| height | **float** | ความสูงของสี่เหลี่ยมที่วาด |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) เมธอด

วาดสี่เหลี่ยมที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสี่เหลี่ยม |
| rect | [Rectangle](../../rectangle/) | วัตถุ [Rectangle](../../rectangle/) ที่ระบุตำแหน่งและขนาดของสี่เหลี่ยมที่วาด |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Pen](../../pen/)
* คลาส [Graphics](../)
* คลาส [Rectangle](../../rectangle/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)