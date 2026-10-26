---
title: insert_auto_shape method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
สร้าง auto shape ใหม่และแทรกลงในคอลเลกชันของรูปทรงที่ตำแหน่งที่ระบุ,
            โดยใช้การจัดรูปแบบเทมเพลตเริ่มต้น.

### คืนค่า

[`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape) ที่สร้างใหม่.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจาก 0 ที่จะใช้แทรก auto shape ใหม่. |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของ auto shape ที่จะใส่. |
| x | **float** | พิกัด x ของกรอบรูปทรง, หน่วยเป็น points. |
| y | **float** | พิกัด y ของกรอบรูปทรง, หน่วยเป็น points. |
| width | **float** | ความกว้างของกรอบรูปทรง, หน่วยเป็น points. |
| height | **float** | ความสูงของกรอบรูปทรง, หน่วยเป็น points. |

## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
สร้าง auto shape ใหม่และแทรกลงในคอลเลกชันของรูปทรงที่ตำแหน่งที่ระบุ,
            โดยอาจกำหนดค่าเริ่มต้นด้วยสไตล์เทมเพลตเริ่มต้น.

### คืนค่า

[`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape) ที่สร้างใหม่.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจาก 0 ที่จะใช้แทรก auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของ auto shape ที่จะใส่. |
| x | **float** | พิกัด x ของกรอบรูปทรง, หน่วยเป็น points. |
| y | **float** | พิกัด y ของกรอบรูปทรง, หน่วยเป็น points. |
| width | **float** | ความกว้างของกรอบรูปทรง, หน่วยเป็น points. |
| height | **float** | ความสูงของกรอบรูปทรง, หน่วยเป็น points. |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (รวมถึงชื่อที่ไม่ว่างเปล่า, สไตล์ง่าย, และข้อความกึ่งกลาง); <br/><br/>            false เพื่อสร้างรูปทรงโดยตั้งค่าทุกคุณสมบัติเป็นค่าเริ่มต้น. |

### ดูเพิ่มเติม
* คลาส [`IAutoShape`](/slides/python-net/th/aspose.slides/iautoshape)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)