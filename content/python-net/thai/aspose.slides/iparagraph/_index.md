---
title: IParagraph class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iparagraph/
---
## IParagraph คลาส

แสดงถึงย่อหน้าของข้อความ

IParagraph type เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`portions`](/slides/python-net/th/aspose.slides/iparagraph/portions/) | คืนค่าชุดของส่วนข้อความ.<br/>            Read-only [`IPortionCollection`](/slides/python-net/th/aspose.slides/iportioncollection). |
| [`paragraph_format`](/slides/python-net/th/aspose.slides/iparagraph/paragraph_format/) | คืนค่าอ็อบเจ็กต์การจัดรูปแบบสำหรับย่อหน้านี้.<br/>            Read-only [`IParagraphFormat`](/slides/python-net/th/aspose.slides/iparagraphformat). |
| [`text`](/slides/python-net/th/aspose.slides/iparagraph/text/) | รับหรือกำหนดข้อความธรรมดาของย่อหน้า.<br/>            Read/write **str**. |
| [`end_paragraph_portion_format`](/slides/python-net/th/aspose.slides/iparagraph/end_paragraph_portion_format/) | ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังจาก<br/>            ส่วนสุดท้าย. |
| [`slide`](/slides/python-net/th/aspose.slides/iparagraph/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/iparagraph/presentation/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/iparagraph/get_image/#) | คืนภาพของย่อหน้า. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/iparagraph/get_image/#float-float) | คืนภาพของย่อหน้าด้วยสเกลที่ระบุ. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/iparagraph/join_portions_with_same_formatting/#) | เชื่อมต่อช่วงข้อความที่มีการจัดรูปแบบเดียวกัน. |
| [`get_rect(self)`](/slides/python-net/th/aspose.slides/iparagraph/get_rect/#) | รับพิกัดของสี่เหลี่ยมที่บรรจุย่อหน้า. สี่เหลี่ยมนี้รวมทุกบรรทัดของ<br/>            ข้อความในย่อหน้า รวมถึงบรรทัดที่ว่างเปล่า. |
| [`get_lines_count(self)`](/slides/python-net/th/aspose.slides/iparagraph/get_lines_count/#) | รับจำนวนบรรทัดในย่อหน้า. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)