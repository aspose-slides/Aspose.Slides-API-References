---
title: insert_auto_shape method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
สร้าง auto shape ใหม่และแทรกลงในคอลเลกชันของ shape ที่ตำแหน่งอินดักซ์ที่ระบุ โดยใช้การจัดรูปแบบเทมเพลตเริ่มต้น

### คืนค่า
ออบเจกต์ [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape) ที่สร้างใหม่.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจาก 0 ที่จะใช้แทรก auto shape ใหม่. |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของ auto shape ที่จะถูกแทรก. |
| x | **float** | พิกัด x ของกรอบ shape หน่วยเป็น point. |
| y | **float** | พิกัด y ของกรอบ shape หน่วยเป็น point. |
| width | **float** | ความกว้างของกรอบ shape หน่วยเป็น point. |
| height | **float** | ความสูงของกรอบ shape หน่วยเป็น point. |

## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
สร้าง auto shape ใหม่และแทรกลงในคอลเลกชันของ shape ที่ตำแหน่งอินดักซ์ที่ระบุ โดยอาจเริ่มต้นด้วยสไตล์เทมเพลตเริ่มต้น

### คืนค่า
ออบเจกต์ [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape) ที่สร้างใหม่.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจาก 0 ที่จะใช้แทรก auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของ auto shape ที่จะถูกแทรก. |
| x | **float** | พิกัด x ของกรอบ shape หน่วยเป็น point. |
| y | **float** | พิกัด y ของกรอบ shape หน่วยเป็น point. |
| width | **float** | ความกว้างของกรอบ shape หน่วยเป็น point. |
| height | **float** | ความสูงของกรอบ shape หน่วยเป็น point. |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (รวมถึงชื่อที่ไม่เป็นค่าว่าง, สไตล์ง่าย, และข้อความจัดกึ่งกลาง); <br/><br/> false เพื่อสร้าง shape ที่มีคุณสมบัติต่าง ๆ เป็นค่าเริ่มต้น. |

### ดูเพิ่มเติม
* คลาส [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)