---
title: IAudio class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iaudio/
---
## IAudio คลาส

Represents an embedded audio file.

The IAudio type exposes the following members:

## คุณสมบัติ

| Property | คำอธิบาย |
| :- | :- |
| [`content_type`](/slides/python-net/th/aspose.slides/iaudio/content_type/) | ส่งคืน MIME type ของไฟล์เสียงที่เข้ารหัสใน [`IAudio.binary_data`](/slides/python-net/th/aspose.slides/iaudio/binary_data).<br/>            อ่านอย่างเดียว **str**. |
| [`binary_data`](/slides/python-net/th/aspose.slides/iaudio/binary_data/) | ส่งคืนสำเนาของข้อมูลเสียง. ในกรณีที่มีข้อมูลจำนวนมาก ควรพิจารณา <br/>            การใช้เมธอด [`IAudio.get_stream`](/slides/python-net/th/aspose.slides/iaudio/get_stream) เพื่อป้องกันการโหลดข้อมูลเสียงลงในหน่วยความจำโดยไม่จำเป็น หรือแม้กระทั่ง OutOfMemoryException.<br/>            อ่านอย่างเดียว **int**[]. |

## เมธอด

| Method | คำอธิบาย |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/th/aspose.slides/iaudio/get_stream/#) | ส่งคืน Stream สำหรับการอ่าน.<br/>            ใช้ 'using' หรือปิด stream หลังการใช้. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)