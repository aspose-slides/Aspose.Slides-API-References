---
title: Audio class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/audio/
---
## คลาส Audio

แสดงไฟล์เสียงที่ฝังอยู่

ประเภท Audio แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`content_type`](/slides/python-net/th/aspose.slides/audio/content_type/) | ส่งคืน MIME type ของไฟล์เสียงที่เข้ารหัสใน [`Audio.binary_data`](/slides/python-net/th/aspose.slides/audio/binary_data).<br/>            อ่านอย่างเดียว **str**. |
| [`binary_data`](/slides/python-net/th/aspose.slides/audio/binary_data/) | ส่งคืนสำเนาข้อมูลของไฟล์เสียง. ในกรณีที่ข้อมูลมีปริมาณมาก ให้พิจารณา <br/>            การใช้เมธอด [`Audio.get_stream`](/slides/python-net/th/aspose.slides/audio/get_stream) เพื่อป้องกันการโหลดข้อมูลของไฟล์เสียง<br/>            เข้าไปในหน่วยความจำโดยไม่จำเป็นหรือแม้กระทั่ง OutOfMemoryException.<br/>            อ่านอย่างเดียว **int**[]. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/th/aspose.slides/audio/get_stream/#) | ส่งคืน Stream สำหรับการอ่าน.<br/>            ใช้ 'using' หรือปิด stream หลังการใช้งาน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)