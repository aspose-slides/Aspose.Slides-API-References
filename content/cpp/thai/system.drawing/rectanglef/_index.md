---
title: RectangleF
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "แทนพื้นที่สี่เหลี่ยมของภาพที่กำหนดโดยพิกัด X และ Y แบบจุดลอยเดี่ยวความแม่นยำเดียวของมุมซ้ายบนและความกว้างและความสูงของมัน. ชนิดนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิง. อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ของชนิดนี้."
type: docs
weight: 248
url: /th/system.drawing/rectanglef/
---
## RectangleF คลาส

Represents a rectangular area of an image defined as single-precision floating point X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class RectangleF
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือไม่. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือไม่. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | กำหนดว่าสี่เหลี่ยมที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือไม่. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | กำหนดว่าสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันและอ็อบเจกต์ที่ระบุเป็นเหมือนกันหรือไม่. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | สร้างอ็อบเจกต์ [RectangleF](./) ใหม่ที่แสดงสี่เหลี่ยมที่มีตำแหน่งขอบตามที่ระบุ. |
| **float** [get_Bottom](./get_bottom/)() const | คืนค่าพิกัด y ของขอบล่างของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **float** [get_Height](./get_height/)() const | คืนค่าความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **bool** [get_IsEmpty](./get_isempty/)() const | กำหนดว่า พิกัด X และ Y ของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน รวมถึงความกว้างและความสูง มีค่าเป็น 0 หรือไม่. |
| **float** [get_Left](./get_left/)() const | คืนค่าพิกัด X ของขอบซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | คืนอินสแตนซ์ของคลาส [PointF](../pointf/) ที่ระบุตำแหน่งของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **float** [get_Right](./get_right/)() const | คืนค่าพิกัด X ของขอบขวาของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | คืนอินสแตนซ์ของคลาส [SizeF](../sizef/) ที่ระบุความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **float** [get_Top](./get_top/)() const | คืนค่าพิกัด Y ของขอบบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **float** [get_Width](./get_width/)() const | คืนค่าความกว้างของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **float** [get_X](./get_x/)() const | คืนค่าพิกัด X ของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| **float** [get_Y](./get_y/)() const | คืนค่าพิกัด Y ของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| int [GetHashCode](./gethashcode/)() const | คืนค่า hash code ของอ็อบเจกต์ปัจจุบัน. |
| void [Inflate](./inflate/)(**float**, **float**) | เพิ่มความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยคงตำแหน่งศูนย์กลางเชิงเรขาคณิตของสี่เหลี่ยมไว้. ความกว้างและความสูงเพิ่มขึ้นในทั้งสองทิศทางตามจำนวนที่ระบุ. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | เพิ่มความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยคงตำแหน่งศูนย์กลางเชิงเรขาคณิตของสี่เหลี่ยมไว้. ความกว้างและความสูงเพิ่มขึ้นในทั้งสองทิศทางตามค่าความกว้างและความสูงของอ็อบเจกต์ขนาดที่ระบุ. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | เพิ่มความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ที่ระบุโดยคงตำแหน่งศูนย์กลางเชิงเรขาคณิตของสี่เหลี่ยมไว้. ความกว้างและความสูงเพิ่มขึ้นในทั้งสองทิศทางตามจำนวนที่ระบุ. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | แทนที่สี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันด้วยสี่เหลี่ยมที่ได้จากการตัดกับสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ที่ระบุ. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | คืนค่าสี่เหลี่ยมที่เป็นผลของการตัดสี่เหลี่ยมที่ระบุ. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | กำหนดว่าสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันและอ็อบเจกต์ที่ระบุมีการตัดกันหรือไม่. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | เลื่อนตำแหน่งของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยจำนวนที่ระบุ. |
| void [Offset](./offset/)(**float**, **float**) | เลื่อนตำแหน่งของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยจำนวนที่ระบุ. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | คืนค่า true เสมอ. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | คืนค่า false เสมอ. |
|  [RectangleF](./rectanglef/)() | สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](./) ที่แสดงสี่เหลี่ยมที่มีพิกัด X และ Y และค่าความกว้างและความสูงตั้งค่าเป็น 0. |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](./) ที่แสดงสี่เหลี่ยมด้วยพิกัดที่ระบุของมุมบนซ้ายและความกว้างและความสูง. |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](./) ที่แสดงสี่เหลี่ยมโดยพิกัดมุมบนซ้ายระบุเป็นอินสแทนซ์ของคลาส [PointF](../pointf/) และความกว้างและความสูงเป็นอินสแทนซ์ของคลาส [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](./) ที่แสดงสี่เหลี่ยมที่เทียบเท่ากับสี่เหลี่ยมที่ระบุ. |
| void [set_Height](./set_height/)(**float**) | ตั้งค่าความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | ตั้งค่าตำแหน่งของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | ตั้งค่าความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| void [set_Width](./set_width/)(**float**) | ตั้งค่าความกว้างของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| void [set_X](./set_x/)(**float**) | ตั้งค่าพิกัด X ของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| void [set_Y](./set_y/)(**float**) | ตั้งค่าพิกัด Y ของมุมบนซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | คืนค่าการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบัน. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | คืนค่าสี่เหลี่ยมที่เป็นผลของการรวมสี่เหลี่ยมที่ระบุ. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Empty](./empty/) | สี่เหลี่ยมว่างเปล่า คือสี่เหลี่ยมที่ค่าตำแหน่งและขนาดเป็นศูนย์. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)