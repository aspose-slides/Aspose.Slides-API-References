---
title: TextFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/textframe/
---
## คลาส TextFrame

เป็นตัวแทนของ TextFrame

TextFrame type มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/th/aspose.slides/textframe/paragraphs/) | คืนรายการของย่อหน้าทั้งหมดในเฟรม<br/>Read-only [`IParagraphCollection`](/slides/python-net/th/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/th/aspose.slides/textframe/text/) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame<br/>Read/write **str**. |
| [`text_frame_format`](/slides/python-net/th/aspose.slides/textframe/text_frame_format/) | คืนออบเจ็กต์การจัดรูปแบบสำหรับ TextFrame นี้<br/>Read-only [`ITextFrameFormat`](/slides/python-net/th/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/textframe/hyperlink_queries/) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย<br/>Read-only [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/th/aspose.slides/textframe/slide/) | คืนสไลด์แม่ของ TextFrame<br/>Read-only [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/textframe/presentation/) | คืนการนำเสนอแม่ของ TextFrame<br/>Read-only [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/th/aspose.slides/textframe/parent_shape/) | คืนรูปทรงแม่หรือ None หากวัตถุแม่ไม่ได้ทำตามอินเทอร์เฟซ IShape<br/>Read-only [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/th/aspose.slides/textframe/parent_cell/) | คืนเซลล์แม่หรือ None หากวัตถุแม่ไม่ได้ทำตามอินเทอร์เฟซ ICell<br/>Read-only [`ICell`](/slides/python-net/th/aspose.slides/icell). |

## วิธีการ

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/th/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/th/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | ไฮไลท์ทุกตำแหน่งที่ตรงกับ regular expression ด้วยสีที่ระบุ |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | ไฮไลท์ทุกตำแหน่งที่ตรงกับ regular expression ด้วยสีที่ระบุ |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/textframe/join_portions_with_same_formatting/#) | รวม runs ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด |
| [`split_text_by_columns(self)`](/slides/python-net/th/aspose.slides/textframe/split_text_by_columns/#) | แบ่งเนื้อหาข้อความของ [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง<br/>โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในเฟรม |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/textframe/replace_regex/#str-str) | แทนที่ผลลัพธ์ที่ตรงกับ regular expression ด้วยสตริงที่ระบุ |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)