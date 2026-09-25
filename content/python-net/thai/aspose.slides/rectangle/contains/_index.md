---
title: contains method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมนี้หรือไม่

### คืนค่า

`True` หากจุดอยู่ภายในสี่เหลี่ยมนี้; มิฉะนั้น `False`.



```python
def contains(self, point):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/th/aspose.slides/point) | จุดที่ต้องทดสอบ. วัตถุใดก็ได้ที่มีแอตทริบิวต์ `x`และ `y` จะได้รับการยอมรับ. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **TypeError** | จำนวนอาร์กิวเมนต์ไม่ถูกต้อง. |


## contains(self, rect) {#rectangle}
กำหนดว่าพื้นที่สี่เหลี่ยมที่แสดงโดย `rect` อยู่ภายในสี่เหลี่ยมนี้อย่างสมบูรณ์หรือไม่

### คืนค่า

`True` หากพื้นที่สี่เหลี่ยมที่แสดงโดย `rect` อยู่ภายในสี่เหลี่ยมนี้อย่างสมบูรณ์; มิฉะนั้น `False`.



```python
def contains(self, rect):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/th/aspose.slides/rectangle) | สี่เหลี่ยมที่ต้องทดสอบ. วัตถุใดก็ได้ที่มีแอตทริบิวต์ `x`, `y`, `width` และ `height` จะได้รับการยอมรับ. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **TypeError** | จำนวนอาร์กิวเมนต์ไม่ถูกต้อง. |


## contains(self, x, y) {#int-int}
กำหนดว่าจุดที่ระบุอยู่ภายในสี่เหลี่ยมนี้หรือไม่

### คืนค่า

`True` หากจุดที่กำหนดโดย `x` และ `y` อยู่ภายในสี่เหลี่ยมนี้; มิฉะนั้น `False`.



```python
def contains(self, x, y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **int** | พิกัด x ของจุดที่ต้องทดสอบ. |
| y | **int** | พิกัด y ของจุดที่ต้องทดสอบ. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **TypeError** | จำนวนอาร์กิวเมนต์ไม่ถูกต้อง. |



### ดูเพิ่มเติม
* คลาส [`Point`](/slides/python-net/th/aspose.slides/point)
* คลาส [`Rectangle`](/slides/python-net/th/aspose.slides/rectangle)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)