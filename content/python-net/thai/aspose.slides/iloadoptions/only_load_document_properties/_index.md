---
title: only_load_document_properties property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## คุณสมบัติ only_load_document_properties
คุณสมบัตินี้มีความหมายเมื่อไฟล์พรีเซนเทชันได้รับการป้องกันด้วยรหัสผ่าน  
ค่า true หมายความว่าจะต้องโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์พรีเซนเทชันที่เข้ารหัสและจะละเว้นรหัสผ่าน  
ค่า false หมายความว่าจะต้องโหลดพรีเซนเทชันที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง  
หากพรีเซนเทชันไม่ได้ถูกเข้ารหัสค่า属性จะถูกละเว้นเสมอ  
หากคุณสมบัติของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่า属性เป็น true จะไม่สามารถโหลดคุณสมบัติของเอกสารได้และจะเกิดข้อยกเว้น  
อ่าน-เขียน **bool**.

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
* คลาส [`ILoadOptions`](/slides/python-net/th/aspose.slides/iloadoptions)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)