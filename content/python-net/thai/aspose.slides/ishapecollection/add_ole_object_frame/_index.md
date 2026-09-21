---
title: add_ole_object_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปที่ท้ายของคอลเลกชันรูปทรง

### ผลลัพธ์

[`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็น points. |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็น points. |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็น points. |
| height | **float** | ความสูงของเฟรม OLE ใหม่, หน่วยเป็น points. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) | ข้อมูล OLE ที่ฝังอยู่ ([`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปที่ท้ายของคอลเลกชันรูปทรง

### ผลลัพธ์

[`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็น points. |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็น points. |
| width | **float** | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็น points. |
| height | **float** | ความสูงของเฟรม OLE ใหม่, หน่วยเป็น points. |
| class_name | **str** | ชื่อคลาสของอ็อบเจ็กต์ OLE. |
| path | **str** | พาธไปยังไฟล์ที่เชื่อมโยง.<br/><br/>พาธนี้จะถูกจัดเก็บตามเดิมในงานนำเสนอ.<br/><br/>หากระบุพาธเชิงสัมพันธ์, ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิด<br/><br/>งานนำเสนอจากไดเรกทอรีอื่น. |



### ดูเพิ่มเติม
* คลาส [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)
* คลาส [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)