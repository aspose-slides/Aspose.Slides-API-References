---
title: add_ole_object_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
สร้างกรอบวัตถุ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง

### คืนค่า

[`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe) ที่สร้างใหม่



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) | ข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังไว้ ([`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)) |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
สร้างกรอบวัตถุ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง

### คืนค่า

[`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe) ที่สร้างใหม่



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบ OLE ใหม่, หน่วยเป็นจุด |
| class_name | **str** | ชื่อคลาสของวัตถุ OLE |
| path | **str** | พาธไปยังไฟล์ที่เชื่อมโยง <br/><br/>พาธนี้จะถูกจัดเก็บตามต้นฉบับในงานนำเสนอ<br/><br/>หากระบุพาธแบบสัมพัทธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิด<br/><br/>งานนำเสนอจากไดเรกทอรีอื่น |



### ดูเพิ่มเติม
* คลาส [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)
* คลาส [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)