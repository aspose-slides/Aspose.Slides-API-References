---
title: insert_connector method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
สร้างรูปร่างเชื่อมต่อใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ, พร้อมใช้สไตล์เทมเพลตเริ่มต้น.

### คืนค่า

[`IConnector`](/slides/python-net/th/aspose.slides/iconnector) ที่สร้างใหม่.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ที่ใช้สำหรับแทรกรูปร่างเชื่อมต่อ |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปร่างเชื่อมต่อที่จะทำการแทรก |
| x | **float** | พิกัด x ของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| y | **float** | พิกัด y ของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| width | **float** | ความกว้างของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| height | **float** | ความสูงของเฟรมเชื่อมต่อ, หน่วยเป็น points |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
สร้างรูปร่างเชื่อมต่อใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ, โดยสามารถเลือกใช้สไตล์เทมเพลตเริ่มต้นได้.

### คืนค่า

[`IConnector`](/slides/python-net/th/aspose.slides/iconnector) ที่สร้างใหม่.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ที่ใช้สำหรับแทรกรูปร่างเชื่อมต่อ |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปร่างเชื่อมต่อที่จะทำการแทรก |
| x | **float** | พิกัด x ของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| y | **float** | พิกัด y ของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| width | **float** | ความกว้างของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| height | **float** | ความสูงของเฟรมเชื่อมต่อ, หน่วยเป็น points |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); false เพื่อสร้างเชื่อมต่อด้วยค่าคุณสมบัติเบื้องต้น |

### ดูเพิ่มเติม
* คลาส [`IConnector`](/slides/python-net/th/aspose.slides/iconnector)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)