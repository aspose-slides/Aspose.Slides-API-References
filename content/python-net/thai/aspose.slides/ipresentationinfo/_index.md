---
title: IPresentationInfo class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ipresentationinfo/
---
## IPresentationInfo คลาส

ข้อมูลเกี่ยวกับไฟล์พรีเซนเทชัน

ประเภท IPresentationInfo เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/th/aspose.slides/ipresentationinfo/is_encrypted/) | รับค่า True หากพรีเซนเทชันที่เชื่อมโยงถูกเข้ารหัส, มิฉะนั้นเป็น False.<br/>            อ่านอย่างเดียว **bool**. |
| [`is_password_protected`](/slides/python-net/th/aspose.slides/ipresentationinfo/is_password_protected/) | รับค่าที่ระบุว่าพรีเซนเทชันที่เชื่อมโยงได้รับการป้องกันด้วยรหัสผ่านเพื่อเปิดหรือไม่. |
| [`is_write_protected`](/slides/python-net/th/aspose.slides/ipresentationinfo/is_write_protected/) | รับค่าที่ระบุว่าพรีเซนเทชันที่เชื่อมโยงได้รับการป้องกันการเขียนหรือไม่. |
| [`load_format`](/slides/python-net/th/aspose.slides/ipresentationinfo/load_format/) | รับรูปแบบของพรีเซนเทชันที่เชื่อมโยง.<br/>            อ่านอย่างเดียว [`LoadFormat`](/slides/python-net/th/aspose.slides/loadformat). |

## เมธอด

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/th/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | เขียนพรีเซนเทชันที่เชื่อมโยงไปยังสตรีม. |
| [`write_binded_presentation(self, file)`](/slides/python-net/th/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | เขียนพรีเซนเทชันที่เชื่อมโยงไปยังไฟล์. |
| [`check_password(self, password)`](/slides/python-net/th/aspose.slides/ipresentationinfo/check_password/#str) | ตรวจสอบว่ารหัสผ่านสำหรับพรีเซนเทชันที่ถูกป้องกันด้วยรหัสผ่านเปิดใช้งานนั้นถูกต้องหรือไม่. |
| [`check_write_protection(self, password)`](/slides/python-net/th/aspose.slides/ipresentationinfo/check_write_protection/#str) | ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขสำหรับพรีเซนเทชันที่ป้องกันการเขียนนั้นถูกต้องหรือไม่. |
| [`read_document_properties(self)`](/slides/python-net/th/aspose.slides/ipresentationinfo/read_document_properties/#) | รับคุณสมบัติเอกสารของพรีเซนเทชันที่เชื่อมโยง. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/th/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | อัปเดตคุณสมบัติของพรีเซนเทชันที่เชื่อมโยง. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)