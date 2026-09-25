---
title: from_known_color method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
สร้างสีจากสีที่กำหนดไว้ล่วงหน้า.<br/>นี่เป็นวิธีเดียวที่สามารถรับสีระบบ (เช่น `KnownColor.CONTROL`): สีระบบไม่ได้เปิดเผยเป็นแอตทริบิวต์ของ `Color` เนื่องจากค่าของมันขึ้นอยู่กับธีมของเดสก์ท็อป ดังนั้นจึงถูกอ่านจาก runtime ของไลบรารี.

### ผลลัพธ์

สีที่เมธอดนี้สร้างไว้



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| known_color | **KnownColor** | สมาชิกของ enumeration `KnownColor` (เป็น `IntEnum` ที่สะท้อน .NET `System.Drawing.KnownColor`) หรือค่าเต็มจำนวนของมัน. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **ValueError** | ค่าที่ให้ไม่เป็นสมาชิกที่ถูกต้องของ `KnownColor`. |



### ดูเพิ่มเติม
* คลาส [`Color`](/slides/python-net/th/aspose.slides/color)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)