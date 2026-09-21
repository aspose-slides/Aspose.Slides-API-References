---
title: insert_connector method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
สร้างรูปแบบเชื่อมต่อใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ,
            โดยใช้สไตล์เทมเพลตเริ่มต้น

### คืนค่า

[`IConnector`](/slides/python-net/th/aspose.slides/iconnector) ที่สร้างขึ้นใหม่.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้เพื่อแทรกรูปแบบเชื่อมต่อ |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปแบบเชื่อมต่อที่จะแทรก |
| x | **float** | พิกัด x ของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| y | **float** | พิกัด y ของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| width | **float** | ความกว้างของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| height | **float** | ความสูงของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
สร้างรูปแบบเชื่อมต่อใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ,
            โดยอาจใช้สไตล์เทมเพลตเริ่มต้น

### คืนค่า

[`IConnector`](/slides/python-net/th/aspose.slides/iconnector) ที่สร้างขึ้นใหม่.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้เพื่อแทรกรูปแบบเชื่อมต่อ |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปแบบเชื่อมต่อที่จะแทรก |
| x | **float** | พิกัด x ของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| y | **float** | พิกัด y ของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| width | **float** | ความกว้างของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| height | **float** | ความสูงของกรอบเชื่อมต่อ, หน่วยเป็นพอยท์ |
| create_from_template | **bool** | true เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่างเปล่า, สไตล์ง่าย);<br/><br/>            false เพื่อสร้างเชื่อมต่อโดยใช้ค่าคุณสมบัติปริยาย |



### ดูเพิ่มเติม
* คลาส [`IConnector`](/slides/python-net/th/aspose.slides/iconnector)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)