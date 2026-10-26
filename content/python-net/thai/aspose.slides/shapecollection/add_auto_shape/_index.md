---
title: add_auto_shape method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
สร้างรูปร่างอัตโนมัติใหม่พร้อมการจัดรูปแบบเริ่มต้นและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง

### ผลลัพธ์

วัตถุที่สร้างใหม่ [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | ค่าของ [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปร่างอัตโนมัติที่จะเพิ่ม |
| x | **float** | พิกัด x ของกรอบรูปร่าง (หน่วยเป็นจุด) |
| y | **float** | พิกัด y ของกรอบรูปร่าง (หน่วยเป็นจุด) |
| width | **float** | ความกว้างของกรอบรูปร่าง (หน่วยเป็นจุด) |
| height | **float** | ความสูงของกรอบรูปร่าง (หน่วยเป็นจุด) |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
สร้างรูปร่างอัตโนมัติใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง โดยอาจเริ่มต้นด้วยการจัดรูปแบบเทมเพลตเริ่มต้น

### ผลลัพธ์

วัตถุที่สร้างใหม่ [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | ค่าของ [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปร่างอัตโนมัติที่จะเพิ่ม |
| x | **float** | พิกัด x ของกรอบรูปร่าง (หน่วยเป็นจุด) |
| y | **float** | พิกัด y ของกรอบรูปร่าง (หน่วยเป็นจุด) |
| width | **float** | ความกว้างของกรอบรูปร่าง (หน.units in points) |
| height | **float** | ความสูงของกรอบรูปร่าง (หน่วยเป็นจุด) |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (สไตล์ง่าย, ข้อความกึ่งกลาง, และชื่อที่ไม่ว่างเปล่า) กับรูปร่างใหม่; false เพื่อสร้างรูปร่างโดยกำหนดค่าทุกคุณสมบัติเป็นค่าเริ่มต้น<br/><br/>            |

### ดูเพิ่มเติม
* คลาส [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)