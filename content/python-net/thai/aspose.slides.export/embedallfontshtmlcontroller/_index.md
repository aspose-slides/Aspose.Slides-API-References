---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController คลาส

คลาสคอนโทรลเลอร์การจัดรูปแบบที่ใช้สำหรับฝังฟอนต์ทั้งหมดของงานนำเสนอในรูปแบบ WOFF.

ประเภท EmbedAllFontsHtmlController แสดงสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | รายละเอียด |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Creates new instance |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Creates new instance |

## เมธอด

| เมธอด | รายละเอียด |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | เรียกเพื่อเขียนส่วนหัวของเอกสาร html เรียกครั้งเดียวต่อการแปลงงานนำเสนอ. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | เรียกเพื่อเขียนส่วนท้ายของเอกสาร html เรียกครั้งเดียวต่อการแปลงงานนำเสนอ. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | เรียกเพื่อเขียนส่วนหัวของสไลด์ html เรียกครั้งเดียวต่อแต่ละสไลด์. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | เรียกเพื่อเขียนส่วนท้ายของสไลด์ html เรียกครั้งเดียวต่อแต่ละสไลด์. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | เรียกก่อนการเรนเดอร์ของ shape เรียกครั้งเดียวต่อแต่ละ shape หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วน html ที่เพิ่มเข้ามาจะถูกแทรกและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | เรียกก่อนการเรนเดอร์ของ shape เรียกครั้งเดียวต่อแต่ละ shape หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วน html ที่เพิ่มเข้ามาจะถูกแทรกและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | เขียนฟอนต์ทั้งหมดที่อยู่ใน [`Presentation`](/slides/python-net/th/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/th/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | เขียนข้อมูลเป็น base64 ลงในเอกสาร HTML เอง |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)