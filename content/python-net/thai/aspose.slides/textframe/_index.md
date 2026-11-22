---
title: TextFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/textframe/
---
## คลาส TextFrame

แสดงถึง TextFrame.

ประเภท TextFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/th/aspose.slides/textframe/paragraphs/) | ส่งคืนรายการของย่อหน้าทั้งหมดในกรอบ.<br/>            อ่านอย่างเดียว [`IParagraphCollection`](/slides/python-net/th/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/th/aspose.slides/textframe/text/) | ดึงหรือกำหนดข้อความธรรมดาสำหรับ TextFrame.<br/>            อ่าน/เขียน **str**. |
| [`text_frame_format`](/slides/python-net/th/aspose.slides/textframe/text_frame_format/) | ส่งคืนอ็อบเจ็กต์การจัดรูปแบบสำหรับอ็อบเจ็กต์ TextFrame นี้.<br/>            อ่านอย่างเดียว [`ITextFrameFormat`](/slides/python-net/th/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/textframe/hyperlink_queries/) | ให้การเข้าถึงลิงก์ไฮเปอร์เท็กซ์ที่บรรจุอยู่ได้ง่าย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/th/aspose.slides/textframe/slide/) | ส่งคืนสไลด์แม่ของ TextFrame.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/textframe/presentation/) | ส่งคืนการนำเสนอแม่ของ TextFrame.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/th/aspose.slides/textframe/parent_shape/) | ส่งคืนรูปร่างแม่หรือ None หากอ็อบเจ็กต์แม่ไม่ได้ทำตามอินเทอร์เฟซ IShape<br/>            อ่านอย่างเดียว [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/th/aspose.slides/textframe/parent_cell/) | ส่งคืนเซลล์แม่หรือ None หากอ็อบเจ็กต์แม่ไม่ได้ทำตามอินเทอร์เฟซ ICell.<br/>            อ่านอย่างเดียว [`ICell`](/slides/python-net/th/aspose.slides/icell). |

## วิธีการ

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/th/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/th/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/textframe/join_portions_with_same_formatting/#) | เชื่อมต่อรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด. |
| [`split_text_by_columns(self)`](/slides/python-net/th/aspose.slides/textframe/split_text_by_columns/#) | แยกเนื้อหาข้อความของ [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe) เป็นอาเรย์ของสตริง, <br/>            โดยแต่ละองค์ประกอบจะสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในกรอบ. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/textframe/replace_regex/#str-str) | แทนที่การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสตริงที่ระบุ. |
| [`get_text_rect(self)`](/slides/python-net/th/aspose.slides/textframe/get_text_rect/#) | รับสี่เหลี่ยมข้อความที่กำหนดโดยเรขาคณิตของรูปร่างแม่. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)