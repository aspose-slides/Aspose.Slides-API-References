---
title: contains method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมนี้หรือไม่.

### คืนค่า

`True` หากจุดอยู่ภายในสี่เหลี่ยมนี้; มิฉะนั้น, `False`.



```python
def contains(self, point):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดที่ต้องทดสอบ. อ็อบเจ็กต์ใด ๆ ที่มีแอตทริบิวต์ `x` และ `y` จะได้รับการยอมรับ. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **TypeError** | จำนวนอาร์กิวเมนต์ไม่ถูกต้อง. |


## contains(self, rect) {#rectanglef}
กำหนดว่าพื้นที่สี่เหลี่ยมที่แสดงโดย `rect` อยู่ภายในสี่เหลี่ยมนี้อย่างเต็มที่หรือไม่.

### คืนค่า

`True` หากพื้นที่สี่เหลี่ยมที่แสดงโดย `rect` อยู่ภายในสี่เหลี่ยมนี้อย่างเต็มที่; มิฉะนั้น, `False`.



```python
def contains(self, rect):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) | สี่เหลี่ยมที่ต้องทดสอบ. อ็อบเจ็กต์ใด ๆ ที่มีแอตทริบิวต์ `x`, `y`, `width` และ `height` จะได้รับการยอมรับ. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **TypeError** | จำนวนอาร์กิวเมนต์ไม่ถูกต้อง. |


## contains(self, x, y) {#float-float}
กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมนี้หรือไม่.

### คืนค่า

`True` หากจุดที่กำหนดด้วย `x` และ `y` อยู่ภายในสี่เหลี่ยมนี้; มิฉะนั้น, `False`.



```python
def contains(self, x, y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของจุดที่ต้องทดสอบ. |
| y | **float** | พิกัด y ของจุดที่ต้องทดสอบ. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **TypeError** | จำนวนอาร์กิวเมนต์ไม่ถูกต้อง. |



### ดูเพิ่มเติม
* คลาส [`PointF`](/slides/python-net/th/aspose.slides/pointf)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)