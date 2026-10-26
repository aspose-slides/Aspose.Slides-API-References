---
title: add_auto_shape method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
สร้างรูปร่างอัตโนมัติใหม่พร้อมการจัดรูปแบบเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง

### คืนค่า

[`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปร่างอัตโนมัติที่จะเพิ่ม. |
| x | **float** | พิกัด x ของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมของรูปร่าง, หน่วยเป็นจุด. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
สร้างรูปร่างอัตโนมัติใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง, โดยอาจเริ่มต้นด้วยการจัดรูปแบบเทมเพลตเริ่มต้น

### คืนค่า

[`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปร่างอัตโนมัติที่จะเพิ่ม. |
| x | **float** | พิกัด x ของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมของรูปร่าง, หน่วยเป็นจุด. |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (สไตล์ง่าย, ข้อความศูนย์กลาง, และชื่อที่ไม่ว่างเปล่า) <br/><br/>            กับรูปร่างใหม่; false เพื่อสร้างรูปร่างโดยตั้งค่าคุณสมบัติต่าง ๆ ทั้งหมดเป็นค่าเริ่มต้น. |



### ดูเพิ่มเติม
* คลาส [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape)
* class [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)