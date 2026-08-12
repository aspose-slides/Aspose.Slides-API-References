---
title: DrawArc()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน
type: docs
weight: 248
url: /th/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method


วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้สำหรับวาดส่วนโค้ง |
| x | **int32_t** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่กำหนดรูปวงรี |
| y | **int32_t** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่กำหนดรูปวงรี |
| width | **int32_t** | ความกว้างของสี่เหลี่ยมที่กำหนดรูปวงรี |
| height | **int32_t** | ความสูงของสี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **int32_t** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของส่วนโค้ง |
| sweepAngle | **int32_t** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของส่วนโค้ง |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method


วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้สำหรับวาดส่วนโค้ง |
| x | **float** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่กำหนดรูปวงรี |
| y | **float** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่กำหนดรูปวงรี |
| width | **float** | ความกว้างของสี่เหลี่ยมที่กำหนดรูปวงรี |
| height | **float** | ความสูงของสี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของส่วนโค้ง |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของส่วนโค้ง |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) method


วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้สำหรับวาดส่วนโค้ง |
| rect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของส่วนโค้ง |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของส่วนโค้ง |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) method


วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้สำหรับวาดส่วนโค้ง |
| rect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของส่วนโค้ง |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของส่วนโค้ง |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)