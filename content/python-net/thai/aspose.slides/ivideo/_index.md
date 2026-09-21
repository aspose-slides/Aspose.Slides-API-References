---
title: IVideo class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ivideo/
---
## IVideo คลาส

แสดงถึงวิดีโอที่ฝังอยู่ในงานนำเสนอ.

ประเภท IVideo เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`content_type`](/slides/python-net/th/aspose.slides/ivideo/content_type/) | คืนค่า MIME type ของวิดีโอที่เข้ารหัสใน [`IVideo.binary_data`](/slides/python-net/th/aspose.slides/ivideo/binary_data).<br/>อ่านอย่างเดียว **str**. |
| [`binary_data`](/slides/python-net/th/aspose.slides/ivideo/binary_data/) | คืนค่าคัดลอกข้อมูลของเสียง. ในกรณีที่จำนวนข้อมูลมากควรพิจารณาการใช้<br/>[`IVideo.get_stream`](/slides/python-net/th/aspose.slides/ivideo/get_stream) method เพื่อป้องกันการโหลดข้อมูลวิดีโอเข้าสู่หน่วยความจำโดยไม่จำเป็น<br/>หรือแม้กระทั่ง OutOfMemoryException.<br/>อ่านอย่างเดียว **int**[]. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/th/aspose.slides/ivideo/get_stream/#) | คืนค่า Stream stream สำหรับการอ่าน.<br/>ใช้ 'using' หรือปิด stream หลังจากใช้. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)