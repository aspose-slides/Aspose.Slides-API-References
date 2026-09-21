---
title: PresentationInfo class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/presentationinfo/
---
## PresentationInfo คลาส

ข้อมูลเกี่ยวกับไฟล์งานนำเสนอ

ประเภท PresentationInfo แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/th/aspose.slides/presentationinfo/is_encrypted/) | ส่งคืน True หากงานนำเสนอที่เชื่อมต่อถูกเข้ารหัส, มิฉะนั้น False.<br/>            Read-only **bool**. |
| [`is_password_protected`](/slides/python-net/th/aspose.slides/presentationinfo/is_password_protected/) | ส่งคืนค่าที่บ่งบอกว่าการนำเสนอที่เชื่อมต่อถูกปกป้องด้วยรหัสผ่านเพื่อเปิดหรือไม่. |
| [`is_write_protected`](/slides/python-net/th/aspose.slides/presentationinfo/is_write_protected/) | ส่งคืนค่าที่บ่งบอกว่าการนำเสนอที่เชื่อมต่อมีการป้องกันการเขียนหรือไม่. |
| [`load_format`](/slides/python-net/th/aspose.slides/presentationinfo/load_format/) | ส่งคืนรูปแบบของการนำเสนอที่เชื่อมต่อ.<br/>            Read-only [`LoadFormat`](/slides/python-net/th/aspose.slides/loadformat). |

## เมธอด

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/th/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | เขียนการนำเสนอที่เชื่อมต่อไปยังสตรีม. |
| [`write_binded_presentation(self, file)`](/slides/python-net/th/aspose.slides/presentationinfo/write_binded_presentation/#str) | เขียนการนำเสนอที่เชื่อมต่อไปยังไฟล์. |
| [`check_password(self, password)`](/slides/python-net/th/aspose.slides/presentationinfo/check_password/#str) | ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับการนำเสนอที่ได้รับการปกป้องด้วยรหัสผ่านเปิดหรือไม่. |
| [`check_write_protection(self, password)`](/slides/python-net/th/aspose.slides/presentationinfo/check_write_protection/#str) | ตรวจสอบว่ารหัสผ่านเพื่อแก้ไขถูกต้องสำหรับการนำเสนอที่ป้องกันการเขียนหรือไม่. |
| [`read_document_properties(self)`](/slides/python-net/th/aspose.slides/presentationinfo/read_document_properties/#) | ส่งคืนคุณสมบัติของเอกสารของการนำเสนอที่เชื่อมต่อ. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/th/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | อัปเดตคุณสมบัติของการนำเสนอที่เชื่อมต่อ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)