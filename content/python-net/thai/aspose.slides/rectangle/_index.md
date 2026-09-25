---
title: Rectangle class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API
description: เก็บชุดของจำนวนเต็มสี่ค่าที่แทนตำแหน่งและขนาดของสี่เหลี่ยม.
type: docs
url: /th/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## คลาส Rectangle

เก็บชุดของจำนวนเต็มสี่ค่าที่แสดงตำแหน่งและขนาดของสี่เหลี่ยม. เข้ากันได้กับ .NET `System.Drawing.Rectangle`.

ประเภท Rectangle เปิดเผยสมาชิกต่อไปนี้:

## ผู้สร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/th/aspose.slides/rectangle/__init__/#int-int-int-int) | สร้างสี่เหลี่ยมด้วยตำแหน่งและขนาดที่ระบุ. ค่าตัวเลขทศนิยมจะถูกตัดเป็นจำนวนเต็ม. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`x`](/slides/python-net/th/aspose.slides/rectangle/x/) | รับค่า x-coordinate ของมุมซ้ายบนของสี่เหลี่ยมนี้.<br/>            อ่านอย่างเดียว **int**. |
| [`y`](/slides/python-net/th/aspose.slides/rectangle/y/) | รับค่า y-coordinate ของมุมซ้ายบนของสี่เหลี่ยมนี้.<br/>            อ่านอย่างเดียว **int**. |
| [`width`](/slides/python-net/th/aspose.slides/rectangle/width/) | รับความกว้างของสี่เหลี่ยมนี้.<br/>            อ่านอย่างเดียว **int**. |
| [`height`](/slides/python-net/th/aspose.slides/rectangle/height/) | รับความสูงของสี่เหลี่ยมนี้.<br/>            อ่านอย่างเดียว **int**. |
| [`left`](/slides/python-net/th/aspose.slides/rectangle/left/) | รับค่า x-coordinate ของขอบซ้ายของสี่เหลี่ยมนี้. เท่ากับ `x`.<br/>            อ่านอย่างเดียว **int**. |
| [`top`](/slides/python-net/th/aspose.slides/rectangle/top/) | รับค่า y-coordinate ของขอบบนของสี่เหลี่ยมนี้. เท่ากับ `y`.<br/>            อ่านอย่างเดียว **int**. |
| [`right`](/slides/python-net/th/aspose.slides/rectangle/right/) | รับค่า x-coordinate ที่เป็นผลรวมของ `x` และ `width` ของสี่เหลี่ยมนี้.<br/>            อ่านอย่างเดียว **int**. |
| [`bottom`](/slides/python-net/th/aspose.slides/rectangle/bottom/) | รับค่า y-coordinate ที่เป็นผลรวมของ `y` และ `height` ของสี่เหลี่ยมนี้.<br/>            อ่านอย่างเดียว **int**. |
| [`is_empty`](/slides/python-net/th/aspose.slides/rectangle/is_empty/) | ระบุว่าคุณสมบัติเชิงตัวเลขทั้งหมดของสี่เหลี่ยมนี้มีค่าเป็นศูนย์หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/th/aspose.slides/rectangle/contains/#int-int) | ตรวจสอบว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมนี้หรือไม่. |
| [`contains(self, point)`](/slides/python-net/th/aspose.slides/rectangle/contains/#point) | ตรวจสอบว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมนี้หรือไม่. |
| [`contains(self, rect)`](/slides/python-net/th/aspose.slides/rectangle/contains/#rectangle) | ตรวจสอบว่าพื้นที่สี่เหลี่ยมที่แทนด้วย `rect` อยู่ภายในสี่เหลี่ยมนี้ทั้งหมดหรือไม่. |


### หมายเหตุ

สี่เหลี่ยมจะถูกเปรียบเทียบโดยตำแหน่งและขนาดด้วย `==` และสามารถใช้เป็นคีย์ของพจนานุกรมหรือเป็นสมาชิกของชุดได้.


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)