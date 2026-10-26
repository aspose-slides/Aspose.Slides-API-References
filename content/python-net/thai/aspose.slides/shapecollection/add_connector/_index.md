---
title: add_connector method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
สร้างรูปเชื่อมต่อใหม่ด้วยสไตล์เทมเพลตเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

### คืนค่า

ออบเจ็กต์ที่สร้างใหม่ [`IConnector`](/slides/python-net/th/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปเชื่อมต่อที่ต้องการเพิ่ม |
| x | **float** | พิกัด x ของกรอบเชื่อมต่อเป็นจุด |
| y | **float** | พิกัด y ของกรอบเชื่อมต่อเป็นจุด |
| width | **float** | ความกว้างของกรอบเชื่อมต่อเป็นจุด |
| height | **float** | ความสูงของกรอบเชื่อมต่อเป็นจุด |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
สร้างรูปเชื่อมต่อใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง, โดยอาจใช้สไตล์เทมเพลตเริ่มต้น

### คืนค่า

ออบเจ็กต์ที่สร้างใหม่ [`IConnector`](/slides/python-net/th/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปเชื่อมต่อที่ต้องการสร้าง |
| x | **float** | พิกัด x ของกรอบเชื่อมต่อเป็นจุด |
| y | **float** | พิกัด y ของกรอบเชื่อมต่อเป็นจุด |
| width | **float** | ความกว้างของกรอบเชื่อมต่อเป็นจุด |
| height | **float** | ความสูงของกรอบเชื่อมต่อเป็นจุด |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); <br/><br/>false เพื่อสร้างเชื่อมต่อด้วยค่าคุณสมบัติเบื้องต้น |



### ดูเพิ่มเติม
* คลาส [`IConnector`](/slides/python-net/th/aspose.slides/iconnector)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)