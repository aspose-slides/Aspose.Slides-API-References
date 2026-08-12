---
title: Rectangle
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงพื้นที่สี่เหลี่ยมของภาพที่กำหนดโดยพิกัด X และ Y เป็นจำนวนเต็มของมุมซ้ายบนและความกว้างและความสูงของมัน. ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิง. อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ของประเภทนี้."
type: docs
weight: 235
url: /th/system.drawing/rectangle/
---
## Rectangle คลาส


Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class Rectangle
```

## เมธอด

| Method | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | สร้างอ็อบเจกต์ [Rectangle](./) จากอ็อบเจกต์ [RectangleF](../rectanglef/) ที่ระบุ โดยทำการปัดค่าโลเคชันและขนาดของอ็อบเจกต์ [RectangleF](../rectanglef/) ไปเป็นค่าจำนวนเต็มที่สูงขึ้นถัดไป |
| **bool** [Contains](./contains/)(int, int) const | ตรวจสอบว่า จุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือไม่ |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | ตรวจสอบว่า จุดที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือไม่ |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | ตรวจสอบว่า สี่เหลี่ยมที่ระบุอยู่ภายในสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันหรือไม่ |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | ตรวจสอบว่าสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันและอ็อบเจกต์ที่ระบุมีความเหมือนกันหรือไม่ |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | สร้างอ็อบเจกต์ [Rectangle](./) ใหม่ที่แสดงสี่เหลี่ยมโดยตำแหน่งขอบที่ระบุ |
| int [get_Bottom](./get_bottom/)() const | คืนค่าพิกัด y ของขอบล่างของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [get_Height](./get_height/)() const | คืนค่าความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| **bool** [get_IsEmpty](./get_isempty/)() const | ตรวจสอบว่า พิกัด X และ Y ของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน รวมทั้งความกว้างและความสูง มีค่าเป็น 0 หรือไม่ |
| int [get_Left](./get_left/)() const | คืนค่าพิกัด X ของขอบซ้ายของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| [Point](../point/) [get_Location](./get_location/)() const | คืนค่าตัวอย่างของคลาส [Point](../point/) ที่ระบุตำแหน่งของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [get_Right](./get_right/)() const | คืนค่าพิกัด X ของขอบขวาของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| [Size](../size/) [get_Size](./get_size/)() const | คืนค่าตัวอย่างของคลาส [Size](../size/) ที่ระบุความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [get_Top](./get_top/)() const | คืนค่าพิกัด Y ของขอบบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [get_Width](./get_width/)() const | คืนค่าความกว้างของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [get_X](./get_x/)() const | คืนค่าพิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [get_Y](./get_y/)() const | คืนค่าพิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| int [GetHashCode](./gethashcode/)() const | คืนค่าแฮชโค้ดของอ็อบเจกต์ปัจจุบัน |
| void [Inflate](./inflate/)(int, int) | เพิ่มความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยคงตำแหน่งศูนย์กลางเรขาคณิตของสี่เหลี่ยมไว้ ความกว้างและความสูงจะเพิ่มในทิศทางทั้งสองตามจำนวนที่ระบุ |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | เพิ่มความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันโดยคงตำแหน่งศูนย์กลางเรขาคณิตของสี่เหลี่ยมไว้ ความกว้างและความสูงจะเพิ่มในทิศทางทั้งสองตามค่าความกว้างและความสูงของอ็อบเจกต์ขนาดที่ระบุ |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | เพิ่มความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ที่ระบุโดยคงตำแหน่งศูนย์กลางเรขาคณิตของสี่เหลี่ยมไว้ ความกว้างและความสูงจะเพิ่มในทิศทางทั้งสองตามจำนวนที่ระบุ |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | แทนที่สี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันด้วยสี่เหลี่ยมที่ได้จากการตัดกันกับสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ที่ระบุ |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | คืนค่าสี่เหลี่ยมที่เป็นผลลัพธ์ของการตัดกันของสี่เหลี่ยมที่ระบุ |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | ตรวจสอบว่าสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันและอ็อบเจกต์ที่ระบุมีการตัดกันหรือไม่ |
| void [Offset](./offset/)(const [Point](../point/)\&) | เลื่อนตำแหน่งของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันด้วยจำนวนที่ระบุ |
| void [Offset](./offset/)(int, int) | เลื่อนตำแหน่งของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบันด้วยจำนวนที่ระบุ |
|  [operator RectangleF](./operator_rectanglef/)() const | คืนค่าอ็อบเจกต์ [RectangleF](../rectanglef/) ที่แสดงสี่เหลี่ยมที่เทียบเท่ากับสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | คืนค่า true เสมอ |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | คืนค่า false เสมอ |
|  [Rectangle](./rectangle/)() | สร้างตัวอย่างใหม่ของอ็อบเจกต์ [Rectangle](./) ที่แสดงสี่เหลี่ยมโดยพิกัด X และ Y รวมถึงค่าความกว้างและความสูงเป็น 0 |
|  [Rectangle](./rectangle/)(int, int, int, int) | สร้างตัวอย่างใหม่ของอ็อบเจกต์ [Rectangle](./) ที่แสดงสี่เหลี่ยมโดยพิกัดที่ระบุของมุมซ้ายบนและความกว้างและความสูง |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | สร้างตัวอย่างใหม่ของอ็อบเจกต์ [Rectangle](./) ที่แสดงสี่เหลี่ยมโดยพิกัดของมุมซ้ายบนระบุเป็นอินสแตนซ์ของคลาส [Point](../point/) และความกว้างและความสูงเป็นอินสแตนซ์ของคลาส [Size](../size/) |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | สร้างตัวอย่างใหม่ของอ็อบเจกต์ [Rectangle](./) ที่แสดงสี่เหลี่ยมที่เทียบเท่ากับสี่เหลี่ยมที่ระบุ |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | สร้างอ็อบเจกต์ [Rectangle](./) จากอ็อบเจกต์ [RectangleF](../rectanglef/) ที่ระบุโดยทำการปัดค่าโลเคชันและขนาดของอ็อบเจกต์ [RectangleF](../rectanglef/) ไปเป็นค่าจำนวนเต็มที่ใกล้ที่สุด |
| void [set_Height](./set_height/)(int) | กำหนดความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_Location](./set_location/)([Point](../point/)) | กำหนดตำแหน่งของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_Size](./set_size/)([Size](../size/)) | กำหนดความกว้างและความสูงของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_Width](./set_width/)(int) | กำหนดความกว้างของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_X](./set_x/)(int) | กำหนดพิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_Y](./set_y/)(int) | กำหนดพิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| [String](../../system/string/) [ToString](./tostring/)() const | คืนค่าการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบัน |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | สร้างอ็อบเจกต์ [Rectangle](./) จากอ็อบเจกต์ [RectangleF](../rectanglef/) ที่ระบุโดยทำการตัดค่าโลเคชันและขนาดของอ็อบเจกต์ [RectangleF](../rectanglef/) ไปเป็นค่าจำนวนเต็มที่ต่ำลงถัดไป |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | คืนค่าสี่เหลี่ยมที่เป็นผลลัพธ์ของการรวมของสี่เหลี่ยมที่ระบุ |

## ฟิลด์

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | สี่เหลี่ยมว่าง คือ สี่เหลี่ยมที่มีค่าโลเคชันและขนาดเป็นศูนย์ |

## ดูเพิ่มเติม

* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)