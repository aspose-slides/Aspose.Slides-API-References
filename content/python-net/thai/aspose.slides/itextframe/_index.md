---
title: ITextFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/itextframe/
---
## ITextFrame คลาส

เป็นตัวแทนของ TextFrame.

ประเภท ITextFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`paragraphs`](/slides/python-net/th/aspose.slides/itextframe/paragraphs/) | ส่งคืนรายการของย่อหน้าทั้งหมดในเฟรม.<br/>            อ่านอย่างเดียว [`IParagraphCollection`](/slides/python-net/th/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/th/aspose.slides/itextframe/text/) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame.<br/>            อ่าน/เขียน **str**. |
| [`text_frame_format`](/slides/python-net/th/aspose.slides/itextframe/text_frame_format/) | ส่งคืนวัตถุการจัดรูปแบบสำหรับอ็อบเจกต์ TextFrame นี้.<br/>            อ่านอย่างเดียว [`ITextFrameFormat`](/slides/python-net/th/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/itextframe/hyperlink_queries/) | ให้การเข้าถึงลิงก์ภายในได้อย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/th/aspose.slides/itextframe/parent_shape/) | ส่งคืนรูปร่างแม่หรือ None หากอ็อบเจกต์แม่ไม่ได้ทำการใช้งานอินเทอร์เฟซ IShape<br/>            อ่านอย่างเดียว [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/th/aspose.slides/itextframe/parent_cell/) | ส่งคืนเซลล์แม่หรือ None หากอ็อบเจกต์แม่ไม่ได้ทำการใช้งานอินเทอร์เฟซ ICell.<br/>            อ่านอย่างเดียว [`ICell`](/slides/python-net/th/aspose.slides/icell). |
| [`slide`](/slides/python-net/th/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/itextframe/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | เน้นข้อความทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | เน้นข้อความทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | เน้นข้อความทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | เน้นการจับคู่ทั้งหมดของนิพจน์ปกติด้วยสีที่ระบุ. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/th/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | เน้นการจับคู่ทั้งหมดของนิพจน์ปกติด้วยสีที่ระบุ. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/itextframe/join_portions_with_same_formatting/#) | รวมช่วงข้อความที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด. |
| [`split_text_by_columns(self)`](/slides/python-net/th/aspose.slides/itextframe/split_text_by_columns/#) | แยกเนื้อหาข้อความของ [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe) เป็นอาเรย์ของสตริง,<br/>            โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในเฟรม. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่ข้อความที่ระบุทั้งหมดด้วยข้อความที่ระบุอื่น. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/itextframe/replace_regex/#str-str) | แทนที่การจับคู่ทั้งหมดของนิพจน์ปกติกับสตริงที่ระบุ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)