---
title: ITextFrame class
second_title: Aspose.Slides สำหรับ Python ผ่านการอ้างอิง API ของ .NET
description: 
type: docs
url: /th/aspose.slides/itextframe/
---
## ITextFrame คลาส

เป็นตัวแทนของ TextFrame.

ประเภท ITextFrame แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`paragraphs`](/slides/python-net/th/aspose.slides/itextframe/paragraphs/) | คืนรายการของทุกย่อหน้าภายในเฟรม<br/>            อ่านอย่างเดียว [`IParagraphCollection`](/slides/python-net/th/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/th/aspose.slides/itextframe/text/) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame<br/>            อ่าน/เขียน **str**. |
| [`text_frame_format`](/slides/python-net/th/aspose.slides/itextframe/text_frame_format/) | คืนอ็อบเจ็กต์การจัดรูปแบบสำหรับอ็อบเจ็กต์ TextFrame นี้<br/>            อ่านอย่างเดียว [`ITextFrameFormat`](/slides/python-net/th/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/itextframe/hyperlink_queries/) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่อยู่ในนั้นอย่างง่ายดาย<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/th/aspose.slides/itextframe/parent_shape/) | คืนรูปร่างพาเรนต์หรือ None ถ้าอ็อบเจ็กต์พาเรนต์ไม่ได้ทำตามอินเทอร์เฟซ IShape<br/>            อ่านอย่างเดียว [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/th/aspose.slides/itextframe/parent_cell/) | คืนเซลล์พาเรนต์หรือ None ถ้าอ็อบเจ็กต์พาเรนต์ไม่ได้ทำตามอินเทอร์เฟซ ICell<br/>            อ่านอย่างเดียว [`ICell`](/slides/python-net/th/aspose.slides/icell). |
| [`slide`](/slides/python-net/th/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/itextframe/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | ไฮไลต์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | ไฮไลต์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | ไฮไลต์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | ไฮไลต์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/th/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | ไฮไลต์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/itextframe/join_portions_with_same_formatting/#) | รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้า |
| [`split_text_by_columns(self)`](/slides/python-net/th/aspose.slides/itextframe/split_text_by_columns/#) | แยกเนื้อหาข้อความของ [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง<br/>            โดยที่แต่ละองค์ประกอบตรงกับคอลัมน์ข้อความแยกต่างหากภายในเฟรม |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/itextframe/replace_regex/#str-str) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)