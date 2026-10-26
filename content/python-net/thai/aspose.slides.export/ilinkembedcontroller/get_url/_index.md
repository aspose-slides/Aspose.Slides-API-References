---
title: get_url method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
คืนค่า URL ไปยังวัตถุภายนอก.
            เมธอดนี้จะถูกเรียกเสมอหาก **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** คืนค่า [`LinkEmbedDecision.LINK`](/slides/python-net/th/aspose.slides.export/linkembeddecision/LINK) และอาจถูกเรียกหาก **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** คืนค่า [`LinkEmbedDecision.EMBED`](/slides/python-net/th/aspose.slides.export/linkembeddecision/EMBED) แต่การฝังเป็นไปไม่ได้.
            สามารถเรียกได้หลายครั้งสำหรับ id ของวัตถุเดียวกัน.

### คืนค่า

URL ของวัตถุภายนอกหรือ None หากวัตถุนี้ควรถูกละเลย.



```python
def get_url(self, id, referrer):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| id | **int** | id ของอ็อบเจ็กต์. id นี้เป็นเอกลักษณ์ทั่วการบันทึกทั้งหมด. |
| referrer | **int** | id ของอ็อบเจ็กต์ที่อ้างอิงหรือ 0 หากวัตถุถูกอ้างอิงโดยเอกสารราก. อาจใช้เพื่อสร้างลิงก์สัมพันธ์. |



### ดูเพิ่มเติม
* คลาส [`ILinkEmbedController`](/slides/python-net/th/aspose.slides.export/ilinkembedcontroller)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)