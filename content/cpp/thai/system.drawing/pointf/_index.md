---
title: PointF
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "แทนคู่ของพิกัด X และ Y แบบจุดลอยเดี่ยว (single-precision floating point) ของจุดบนระนาบสองมิติ ชนิดนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง ห้ามใช้คลาส System::SmartPtr เพื่อจัดการวัตถุของชนิดนี้"
type: docs
weight: 222
url: /th/system.drawing/pointf/
---
## PointF คลาส

แสดงคู่ของพิกัด X และ Y แบบจุดลอยเดี่ยว (single-precision floating point) ของจุดบนระนาบสองมิติ ชนิดนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง ห้ามใช้คลาส [System::SmartPtr](../../system/smartptr/) เพื่อจัดการวัตถุของชนิดนี้。

```cpp
class PointF
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | เพิ่มค่าความกว้างและความสูงของอ็อบเจกต์ [SizeF](../sizef/) ที่ระบุไปยังค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](./) ที่ระบุตามลำดับ |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | เพิ่มค่าความกว้างและความสูงของอ็อบเจกต์ [Size](../size/) ที่ระบุไปยังค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](./) ที่ระบุตามลำดับ |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | ตรวจสอบว่าวัตถุปัจจุบันและวัตถุที่ระบุเท่ากันหรือไม่ คือ แทนคู่พิกัด X และ Y เดียวกัน |
| **bool** [get_IsEmpty](./get_isempty/)() const | ตรวจสอบว่าค่าพิกัด X และ Y ทั้งสองเป็น 0 หรือไม่ |
| **float** [get_X](./get_x/)() const | คืนค่าพิกัด X ที่วัตถุปัจจุบันแสดง |
| **float** [get_Y](./get_y/)() const | คืนค่าพิกัด Y ที่วัตถุปัจจุบันแสดง |
| int [GetHashCode](./gethashcode/)() const | คืนค่าแฮชโค้ดของวัตถุปัจจุบัน |
| **bool** [IsNull](./isnull/)() const | คืนค่า false เสมอ |
| explicit  [operator bool](./operator_bool/)() | คืนค่า true เสมอ |
| [PointF](./pointf/)() | สร้างอ็อบเจกต์ [PointF](./) ใหม่และกำหนดค่าพิกัด X และ Y เป็น 0 |
| [PointF](./pointf/)(**float**, **float**) | สร้างอ็อบเจกต์ [PointF](./) ใหม่และกำหนดค่าเริ่มต้นด้วยค่าที่ระบุ |
| [PointF](./pointf/)(const [SizeF](../sizef/)\&) | สร้างอ็อบเจกต์ [PointF](./) ใหม่และกำหนดค่าพิกัด X และ Y ด้วยค่าความกว้างและความสูงของอ็อบเจกต์ [SizeF](../sizef/) ที่ระบุตามลำดับ |
| void [set_X](./set_x/)(**float**) | ตั้งค่าพิกัด X ของวัตถุปัจจุบัน |
| void [set_Y](./set_y/)(**float**) | ตั้งค่าพิกัด Y ของวัตถุปัจจุบัน |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | ลบค่าความกว้างและความสูงของอ็อบเจกต์ [SizeF](../sizef/) ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](./) ที่ระบุตามลำดับ |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | ลบค่าความกว้างและความสูงของอ็อบเจกต์ [Size](../size/) ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](./) ที่ระบุตามลำดับ |
| [System::String](../../system/string/) [ToString](./tostring/)() const | คืนค่าการแสดงผลเป็นสตริงของคู่พิกัด X และ Y ของวัตถุปัจจุบัน |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Empty](./empty/) | อินสแตนซ์ว่างของคลาส [PointF](./) ที่ค่าพิกัด X และ Y เป็น 0 |

## ดูเพิ่มเติม

* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)