---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded คุณสมบัติ
This property makes sense, if presentation file is password protected and document
            คุณสมบัติของไฟล์นี้เป็นสาธารณะ.
            ค่าจริงหมายความว่าเฉพาะคุณสมบัติของเอกสารจะถูกโหลดจากไฟล์ที่เข้ารหัส
            ไฟล์งานนำเสนอโดยไม่มีการใช้รหัสผ่าน.
            ค่าผิดหมายความว่าการนำเสนอที่เข้ารหัสทั้งหมดจะถูกโหลดด้วยการใช้รหัสผ่านที่ถูกต้อง
            รหัสผ่าน ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสาร.
            หากการนำเสนอไม่ได้ถูกเข้ารหัส ค่าของคุณสมบัติจะแสดงเป็นเท็เสมอ.
            หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะ ค่าของคุณสมบัติจะแสดงเป็นเท็เสมอ.
            หาก PresentationEx.EncryptDocumentProperties เป็น true แล้วค่า IsOnlyDocumentPropertiesLoaded
            ค่าของคุณสมบัติจะแสดงเป็นเท็เสมอ.
            อ่านอย่างเดียว **bool**.

### คำนิยาม:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IProtectionManager`](/slides/python-net/th/aspose.slides/iprotectionmanager)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)