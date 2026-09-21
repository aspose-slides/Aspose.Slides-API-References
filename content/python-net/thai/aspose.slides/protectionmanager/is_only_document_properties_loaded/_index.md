---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded คุณสมบัติ
คุณสมบัตินี้มีความหมายเมื่อไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติเขียนเชิงของไฟล์นี้เป็นสาธารณะ
ค่าจริงหมายถึงว่าจะโหลดเฉพาะคุณสมบัติเขียนเชิงของไฟล์การนำเสนอที่เข้ารหัสโดยไม่ใช้รหัสผ่าน
ค่าผิดหมายถึงว่าจะโหลดการนำเสนอทั้งหมดที่เข้ารหัสโดยใช้รหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติเขียนเชิงเท่านั้น
ถ้าไฟล์การนำเสนอไม่ได้เข้ารหัสค่าคุณสมบัติจึงจะเป็นเท็เสมอ
ถ้าคุณสมบัติเขียนเชิงของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะค่าคุณสมบัติจึงเป็นเท็เสมอ
ถ้า Presentation.EncryptDocumentProperties เป็นจริงแล้วค่าคุณสมบัติ IsOnlyDocumentPropertiesLoaded จะเป็นเท็เสมอ
อ่านอย่างเดียว **bool**.

### คำนิยาม:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`ProtectionManager`](/slides/python-net/th/aspose.slides/protectionmanager)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)