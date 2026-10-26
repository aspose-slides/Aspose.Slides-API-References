---
title: only_load_document_properties property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties คุณสมบัติ
คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน
            ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน
            ค่า false หมายความว่าจะโหลดไฟล์งานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง
            หากไฟล์งานนำเสนอไม่ได้เข้ารหัสคุณสมบัติจึงจะถูกละเว้นเสมอ
            หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะและค่าเป็น true แล้วคุณสมบัติของเอกสารไม่สามารถโหลดได้และจะเกิดข้อยกเว้น
            อ่าน/เขียน **bool**.

### คำนิยาม:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`LoadOptions`](/slides/python-net/th/aspose.slides/loadoptions)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)