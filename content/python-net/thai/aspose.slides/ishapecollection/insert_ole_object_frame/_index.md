---
title: insert_ole_object_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
สร้างกรอบวัตถุ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

### Returns

กรอบวัตถุ OLE ที่สร้างใหม่ [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรกกรอบวัตถุ OLE |
| x | **float** | พิกัด x ของกรอบ OLE ใหม่ หน่วยเป็น points |
| y | **float** | พิกัด y ของกรอบ OLE ใหม่ หน่วยเป็น points |
| width | **float** | ความกว้างของกรอบ OLE ใหม่ หน่วยเป็น points |
| height | **float** | ความสูงของกรอบ OLE ใหม่ หน่วยเป็น points |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) | ข้อมูล OLE ที่ฝังอยู่ ([`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)) |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
สร้างกรอบวัตถุ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

### Returns

กรอบวัตถุ OLE ที่สร้างใหม่ [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรกกรอบวัตถุ OLE |
| x | **float** | พิกัด x ของกรอบ OLE ใหม่ หน่วยเป็น points |
| y | **float** | พิกัด y ของกรอบ OLE ใหม่ หน่วยเป็น points |
| width | **float** | ความกว้างของกรอบ OLE ใหม่ หน่วยเป็น points |
| height | **float** | ความสูงของกรอบ OLE ใหม่ หน่วยเป็น points |
| class_name | **str** | ชื่อคลาสของวัตถุ OLE |
| path | **str** | เส้นทางไปยังไฟล์ที่เชื่อมโยง <br/><br/>เส้นทางนี้จะถูกเก็บไว้โดยไม่เปลี่ยนแปลงในงานนำเสนอ.<br/><br/>หากระบุเส้นทางแบบสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีที่แตกต่าง. |



### See Also
* คลาส [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)
* คลาส [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)