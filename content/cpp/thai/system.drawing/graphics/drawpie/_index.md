---
title: DrawPie()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน.
type: docs
weight: 261
url: /th/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) เมธอด

วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้ในการวาดพาย |
| x | **int32_t** | พิกัด X ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| y | **int32_t** | พิกัด Y ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| width | **int32_t** | ความกว้างของสี่เหลี่ยมที่กำหนดรูปวงรี |
| height | **int32_t** | ความสูงของสี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **int32_t** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | **int32_t** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) เมธอด

วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้ในการวาดพาย |
| x | **float** | พิกัด X ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| y | **float** | พิกัด Y ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| width | **float** | ความกว้างของสี่เหลี่ยมที่กำหนดรูปวงรี |
| height | **float** | ความสูงของสี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) เมธอด

วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้ในการวาดพาย |
| rect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) เมธอด

วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้ในการวาดพาย |
| rect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Pen](../../pen/)
* คลาส [Graphics](../)
* คลาส [Rectangle](../../rectangle/)
* คลาส [RectangleF](../../rectanglef/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)