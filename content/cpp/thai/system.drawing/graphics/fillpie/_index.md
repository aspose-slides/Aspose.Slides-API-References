---
title: FillPie()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เติมพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน.
type: docs
weight: 274
url: /th/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) method

เติมพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | แปรงที่ใช้เมื่อเติมพาย |
| x | int | พิกัด X ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| y | int | พิกัด Y ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| width | int | ความกว้างของสี่เหลี่ยมที่กำหนดรูปวงรี |
| height | int | ความสูงของสี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | int | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | int | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) method

เติมพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | แปรงที่ใช้เมื่อเติมพาย |
| x | **float** | พิกัด X ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| y | **float** | พิกัด Y ของมุมบนซ้ายของสี่เหลี่ยมที่กำหนดรูปวงรี |
| width | **float** | ความกว้างของสี่เหลี่ยมที่กำหนดรูปวงรี |
| height | **float** | ความสูงของสี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) method

เติมพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | แปรงที่ใช้เมื่อเติมพาย |
| rect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่กำหนดรูปวงรี |
| startAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจากแกน X ไปยังจุดเริ่มต้นของพาย |
| sweepAngle | **float** | มุมเป็นองศาที่วัดตามเข็มนาฬิกาจาก **startAngle** ไปยังจุดสิ้นสุดของพาย |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Brush](../../brush/)
* คลาส [Graphics](../)
* คลาส [Rectangle](../../rectangle/)
* เนมสเปซ [System::Drawing](../../)
* Library [Aspose.Slides](../../../)