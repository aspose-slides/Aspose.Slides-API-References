---
title: ITextFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/itextframe/
---
## ITextFrame คลาส

Represents a TextFrame.

The ITextFrame type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`paragraphs`](/slides/python-net/th/aspose.slides/itextframe/paragraphs/) | ส่งคืนรายการของย่อหน้าทั้งหมดในเฟรม.<br/>            อ่านอย่างเดียว [`IParagraphCollection`](/slides/python-net/th/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/th/aspose.slides/itextframe/text/) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame.<br/>            อ่าน/เขียน **str**. |
| [`text_frame_format`](/slides/python-net/th/aspose.slides/itextframe/text_frame_format/) | ส่งคืนออบเจ็กต์การจัดรูปแบบสำหรับออบเจ็กต์ TextFrame นี้.<br/>            อ่านอย่างเดียว [`ITextFrameFormat`](/slides/python-net/th/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/itextframe/hyperlink_queries/) | ให้การเข้าถึงลิงก์ที่ฝังอยู่ได้อย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/th/aspose.slides/itextframe/parent_shape/) | ส่งคืน shape พาเรนท์หรือ None หากออบเจ็กต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ IShape<br/>            อ่านอย่างเดียว [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/th/aspose.slides/itextframe/parent_cell/) | ส่งคืน cell พาเรนท์หรือ None หากออบเจ็กต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ ICell.<br/>            อ่านอย่างเดียว [`ICell`](/slides/python-net/th/aspose.slides/icell). |
| [`slide`](/slides/python-net/th/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/itextframe/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | ไฮไลท์ทั้งหมดของข้อความตัวอย่างที่ตรงกันด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | ไฮไลท์ทั้งหมดของข้อความตัวอย่างที่ตรงกันด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | ไฮไลท์ทั้งหมดของข้อความตัวอย่างที่ตรงกันด้วยสีที่ระบุ. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | ไฮไลท์ทั้งหมดของการจับคู่กับ regular expression ด้วยสีที่ระบุ. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/th/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | ไฮไลท์ทั้งหมดของการจับคู่กับ regular expression ด้วยสีที่ระบุ. |
| [`get_text_rect(self)`](/slides/python-net/th/aspose.slides/itextframe/get_text_rect/#) | รับสี่เหลี่ยมข้อความที่กำหนดโดยรูปทรงของ shape พาเรนท์. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/itextframe/join_portions_with_same_formatting/#) | รวม runs ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด. |
| [`split_text_by_columns(self)`](/slides/python-net/th/aspose.slides/itextframe/split_text_by_columns/#) | แยกเนื้อหาข้อความของ [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง, <br/>            ที่แต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในเฟรม. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความที่ระบุอื่น. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/itextframe/replace_regex/#str-str) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)