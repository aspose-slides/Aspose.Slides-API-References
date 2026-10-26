---
title: IProtectionManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iprotectionmanager/
---
## IProtectionManager คลาส

การจัดการการป้องกันด้วยรหัสผ่านของการนำเสนอ.

ประเภท IProtectionManager เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/th/aspose.slides/iprotectionmanager/encrypt_document_properties/) | คุณสมบัตินี้มีความหมาย หากการนำเสนอถูกป้องกันด้วยรหัสผ่าน.<br/>            หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ.<br/>            หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะในขณะที่การนำเสนอถูกเข้ารหัส.<br/>            อ่าน/เขียน **bool**. |
| [`is_encrypted`](/slides/python-net/th/aspose.slides/iprotectionmanager/is_encrypted/) | รับค่าที่บ่งชี้ว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/th/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | คุณสมบัตินี้มีความหมาย หากไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารของไฟล์นี้เป็นสาธารณะ.<br/>            ค่า true หมายถึงว่าเฉพาะคุณสมบัติของเอกสารเท่านั้นที่จะถูกโหลดจากไฟล์การนำเสนอที่เข้ารหัสโดยไม่ใช้รหัสผ่าน.<br/>            ค่า false หมายถึงว่าไฟล์การนำเสนอที่เข้ารหัสทั้งหมดจะถูกโหลดโดยใช้รหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสารเท่านั้น.<br/>            หากการนำเสนอไม่ได้ถูกเข้ารหัสค่าคุณสมบัติจะแม่น้ำ false เสมอ.<br/>            หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะค่าคุณสมบัติจะแม่น้ำ false เสมอ.<br/>            หาก PresentationEx.EncryptDocumentProperties เป็น true แล้วค่า IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ.<br/>            อ่านอย่างเดียว **bool**. |
| [`is_write_protected`](/slides/python-net/th/aspose.slides/iprotectionmanager/is_write_protected/) | รับค่าที่บ่งชี้ว่าการนำเสนอนี้ถูกป้องกันการเขียนหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`encryption_password`](/slides/python-net/th/aspose.slides/iprotectionmanager/encryption_password/) | คืนค่ารหัสผ่านการเข้ารหัส.<br/>            อ่านอย่างเดียว **str**. |
| [`read_only_recommended`](/slides/python-net/th/aspose.slides/iprotectionmanager/read_only_recommended/) | รับหรือกำหนดคำแนะนำแบบอ่านอย่างเดียว.<br/>            อ่าน/เขียน **bool**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/th/aspose.slides/iprotectionmanager/encrypt/#str) | เข้ารหัส Presentation ด้วยรหัสผ่านที่ระบุ. |
| [`remove_encryption(self)`](/slides/python-net/th/aspose.slides/iprotectionmanager/remove_encryption/#) | ลบการเข้ารหัส. |
| [`set_write_protection(self, password)`](/slides/python-net/th/aspose.slides/iprotectionmanager/set_write_protection/#str) | ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอนี้ด้วยรหัสผ่านที่ระบุ. |
| [`remove_write_protection(self)`](/slides/python-net/th/aspose.slides/iprotectionmanager/remove_write_protection/#) | ลบการป้องกันการเขียนสำหรับการนำเสื่อนี้. |
| [`check_write_protection(self, password)`](/slides/python-net/th/aspose.slides/iprotectionmanager/check_write_protection/#str) | กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อทำการแก้ไขหรือไม่. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)