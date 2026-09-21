---
title: add_connector method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
สร้างรูปทรงเชื่อมต่อใหม่โดยใช้สไตล์เทมเพลตเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

### ผลลัพธ์

[`IConnector`](/slides/python-net/th/aspose.slides/iconnector) ที่สร้างใหม่



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปเชื่อมต่อที่ต้องการเพิ่ม |
| x | **float** | พิกัด x ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
สร้างรูปทรงเชื่อมต่อใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง, สามารถใช้สไตล์เทมเพลตเริ่มต้นได้ตามต้องการ

### ผลลัพธ์

[`IConnector`](/slides/python-net/th/aspose.slides/iconnector) ที่สร้างใหม่



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) ของรูปเชื่อมต่อที่ต้องการสร้าง |
| x | **float** | พิกัด x ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมของตัวเชื่อมต่อ, หน่วยเป็นจุด |
| create_from_template | **bool** | True เพื่อใช้สไตล์เทมเพลตเริ่มต้น (ชื่อไม่ว่างเปล่า, สไตล์ง่าย); <br/><br/>false เพื่อสร้างตัวเชื่อมต่อด้วยค่าคุณสมบัติปริยาย |



### ดูเพิ่มเติม
* คลาส [`IConnector`](/slides/python-net/th/aspose.slides/iconnector)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)