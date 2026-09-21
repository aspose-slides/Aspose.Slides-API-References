---
title: insert_ole_object_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
สร้างเฟรมอ็อบเจกต์ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### Returns

อ็อบเจกต์ OLE ที่สร้างใหม่ [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกเฟรมอ็อบเจกต์ OLE |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) | ข้อมูล OLE ที่ฝังอยู่ ([`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)) |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
สร้างเฟรมอ็อบเจกต์ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### Returns

เฟรมอ็อบเจกต์ OLE ที่สร้างใหม่



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกเฟรมอ็อบเจกต์ OLE |
| x | **float** | พิกัด x ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรม OLE ใหม่ หน่วยเป็นจุด |
| class_name | **str** | ชื่อคลาสของอ็อบเจกต์ OLE |
| path | **str** | พาธไปยังไฟล์ที่เชื่อมโยง <br/><br/>พาธนี้จะถูกเก็บไว้โดยตรงในงานนำเสนอ.<br/><br/>หากระบุพาธแบบสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีที่ต่างออกไป. |



### See Also
* คลาส [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)
* คลาส [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)