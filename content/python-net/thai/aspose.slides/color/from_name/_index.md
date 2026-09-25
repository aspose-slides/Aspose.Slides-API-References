---
title: from_name method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
สร้างสีจากชื่อของสีที่กำหนดไว้ล่วงหน้าที่ระบุ<br/>การค้นหาไม่สนใจขนาดตัวอักษรและละเว้นขีดล่างและช่องว่าง: `"LightBlue"`, `"lightblue"` และ `"light_blue"` ทั้งหมดจะถูกแมปเป็น `Color.light_blue`. ดูหน้าคลาส [`Color`](/slides/python-net/th/aspose.slides/color) สำหรับรายการสีที่กำหนดล่วงหน้า.

### คืนค่า

สีที่ระบุชื่อ.



```python
@staticmethod
def from_name(name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| name | **str** | สตริงที่เป็นชื่อของสีที่กำหนดไว้ล่วงหน้า. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **ValueError** | ชื่อไม่ใช่ชื่อของสีที่กำหนดไว้ล่วงหน้า. |
| **TypeError** | ชื่อไม่ใช่สตริง. |



### ดูเพิ่มเติม
* คลาส [`Color`](/slides/python-net/th/aspose.slides/color)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)