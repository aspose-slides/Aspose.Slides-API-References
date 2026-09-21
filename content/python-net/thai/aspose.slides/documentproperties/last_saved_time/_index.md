---
title: last_saved_time property
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time คุณสมบัติ
Returns the date a presentation was last modified.
Values are in UTC.
Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process).
Can be changed via DocumentProperties instance returning by method [`IPresentationInfo.read_document_properties`](/slides/python-net/th/aspose.slides/ipresentationinfo/read_document_properties)
Please see the example in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary.

### คำนิยาม:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`DocumentProperties`](/slides/python-net/th/aspose.slides/documentproperties)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)