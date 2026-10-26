---
title: ProtectionManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/protectionmanager/
---
## ProtectionManager คลาส

การจัดการการป้องกันรหัสผ่านของงานนำเสนอ.

ประเภท ProtectionManager เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/th/aspose.slides/protectionmanager/encrypt_document_properties/) | คุณสมบัตินี้มีความหมาย หากงานนำเสนอได้รับการป้องกันด้วยรหัสผ่าน.<br/>            หากเป็น true เอกสารคุณสมบัติจะถูกเข้ารหัสในไฟล์งานนำเสนอ.<br/>            หากเป็น false เอกสารคุณสมบัติจะเป็นสาธารณะขณะที่งานนำเสนอถูกเข้ารหัส.<br/>            อ่าน/เขียน **bool**. |
| [`is_encrypted`](/slides/python-net/th/aspose.slides/protectionmanager/is_encrypted/) | รับค่าที่บ่งชี้ว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/th/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอได้รับการป้องกันด้วยรหัสผ่านและเอกสาร<br/>            คุณสมบัติของไฟล์นี้เป็นสาธารณะ.<br/>            ค่า true หมายความว่ามีการโหลดเฉพาะเอกสารคุณสมบัติจากไฟล์งานนำเสนอที่เข้ารหัสโดยไม่ใช้รหัสผ่าน.<br/>            ค่า false หมายความว่ามีการโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะเอกสารคุณสมบัติ.<br/>            หากงานนำเสนอไม่ถูกเข้ารหัส ค่าคุณสมบัติจะแสดงเป็น false เสมอ.<br/>            หากเอกสารคุณสมบัติของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะ ค่าคุณสมบัติจะแสดงเป็น false เสมอ.<br/>            หาก Presentation.EncryptDocumentProperties เป็น true แล้วค่าคุณสมบัติ IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ.<br/>            อ่านอย่างเดียว **bool**. |
| [`is_write_protected`](/slides/python-net/th/aspose.slides/protectionmanager/is_write_protected/) | รับค่าที่บ่งชี้ว่างานนำเสนอนี้ถูกป้องกันการเขียนหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`encryption_password`](/slides/python-net/th/aspose.slides/protectionmanager/encryption_password/) | รับรหัสผ่านที่ใช้สำหรับการเข้ารหัสงานนำเสนอ.<br/>            อ่านอย่างเดียว **str**. |
| [`read_only_recommended`](/slides/python-net/th/aspose.slides/protectionmanager/read_only_recommended/) | รับหรือกำหนดคำแนะนำแบบอ่านอย่างเดียว.<br/>            อ่าน/เขียน **bool**. |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/th/aspose.slides/protectionmanager/encrypt/#str) | เข้ารหัส Presentation ด้วยรหัสผ่านที่ระบุ. |
| [`remove_encryption(self)`](/slides/python-net/th/aspose.slides/protectionmanager/remove_encryption/#) | ลบการเข้ารหัส. |
| [`set_write_protection(self, password)`](/slides/python-net/th/aspose.slides/protectionmanager/set_write_protection/#str) | ตั้งการป้องกันการเขียนสำหรับงานนำเสนอนี้ด้วยรหัสผ่านที่ระบุ. |
| [`remove_write_protection(self)`](/slides/python-net/th/aspose.slides/protectionmanager/remove_write_protection/#) | ลบการป้องกันการเขียนสำหรับงานนำเสนี้. |
| [`check_write_protection(self, password)`](/slides/python-net/th/aspose.slides/protectionmanager/check_write_protection/#str) | ตรวจสอบว่างานนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)