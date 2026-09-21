---
title: ILineFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ilineformat/
---
## ILineFormat คลาส

แสดงรูปแบบของเส้น

ประเภท ILineFormat เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_format_not_defined`](/slides/python-net/th/aspose.slides/ilineformat/is_format_not_defined/) | คืนค่า true หากรูปแบบเส้นยังไม่ได้กำหนด (ตามที่เพิ่งสร้าง, ค่าเริ่มต้น).<br/>            อ่านอย่างเดียว **bool**. |
| [`fill_format`](/slides/python-net/th/aspose.slides/ilineformat/fill_format/) | คืนค่าแบบเติมของเส้น.<br/>            อ่านอย่างเดียว [`ILineFillFormat`](/slides/python-net/th/aspose.slides/ilinefillformat). |
| [`sketch_format`](/slides/python-net/th/aspose.slides/ilineformat/sketch_format/) | คืนค่าแบบสเก็ตของเส้น.<br/>            อ่านอย่างเดียว [`ISketchFormat`](/slides/python-net/th/aspose.slides/isketchformat). |
| [`width`](/slides/python-net/th/aspose.slides/ilineformat/width/) | คืนค่าหรือกำหนดความกว้างของเส้น.<br/>            อ่าน/เขียน **float**. |
| [`dash_style`](/slides/python-net/th/aspose.slides/ilineformat/dash_style/) | คืนค่าหรือกำหนดรูปแบบเส้นขีด.<br/>            อ่าน/เขียน [`LineDashStyle`](/slides/python-net/th/aspose.slides/linedashstyle). |
| [`custom_dash_pattern`](/slides/python-net/th/aspose.slides/ilineformat/custom_dash_pattern/) | คืนค่าหรือกำหนดแพทเทิร์นจุดขีดแบบกำหนดเอง.<br/>            อ่าน/เขียน **float**[]. |
| [`cap_style`](/slides/python-net/th/aspose.slides/ilineformat/cap_style/) | คืนค่าหรือกำหนดสไตล์ปลายเส้น.<br/>            อ่าน/เขียน [`LineCapStyle`](/slides/python-net/th/aspose.slides/linecapstyle). |
| [`style`](/slides/python-net/th/aspose.slides/ilineformat/style/) | คืนค่าหรือกำหนดสไตล์เส้น.<br/>            อ่าน/เขียน [`LineStyle`](/slides/python-net/th/aspose.slides/linestyle). |
| [`alignment`](/slides/python-net/th/aspose.slides/ilineformat/alignment/) | คืนค่าหรือกำหนดการจัดตำแหน่งเส้น.<br/>            อ่าน/เขียน [`LineAlignment`](/slides/python-net/th/aspose.slides/linealignment). |
| [`join_style`](/slides/python-net/th/aspose.slides/ilineformat/join_style/) | คืนค่าหรือกำหนดสไตล์การเชื่อมต่อของเส้น.<br/>            อ่าน/เขียน [`LineJoinStyle`](/slides/python-net/th/aspose.slides/linejoinstyle). |
| [`miter_limit`](/slides/python-net/th/aspose.slides/ilineformat/miter_limit/) | คืนค่าหรือกำหนดขีดจำกัดมิตเตอร์ของเส้น.<br/>            อ่าน/เขียน **float**. |
| [`begin_arrowhead_style`](/slides/python-net/th/aspose.slides/ilineformat/begin_arrowhead_style/) | คืนค่าหรือกำหนดสไตล์หัวศรที่จุดเริ่มต้นของเส้น.<br/>            อ่าน/เขียน [`LineArrowheadStyle`](/slides/python-net/th/aspose.slides/linearrowheadstyle). |
| [`end_arrowhead_style`](/slides/python-net/th/aspose.slides/ilineformat/end_arrowhead_style/) | คืนค่าหรือกำหนดสไตล์หัวศรที่จุดสิ้นสุดของเส้น.<br/>            อ่าน/เขียน [`LineArrowheadStyle`](/slides/python-net/th/aspose.slides/linearrowheadstyle). |
| [`begin_arrowhead_width`](/slides/python-net/th/aspose.slides/ilineformat/begin_arrowhead_width/) | คืนค่าหรือกำหนดความกว้างหัวศรที่จุดเริ่มต้นของเส้น.<br/>            อ่าน/เขียน [`LineArrowheadWidth`](/slides/python-net/th/aspose.slides/linearrowheadwidth). |
| [`end_arrowhead_width`](/slides/python-net/th/aspose.slides/ilineformat/end_arrowhead_width/) | คืนค่าหรือกำหนดความกว้างหัวศรที่จุดสิ้นสุดของเส้น.<br/>            อ่าน/เขียน [`LineArrowheadWidth`](/slides/python-net/th/aspose.slides/linearrowheadwidth). |
| [`begin_arrowhead_length`](/slides/python-net/th/aspose.slides/ilineformat/begin_arrowhead_length/) | คืนค่าหรือกำหนดความยาวหัวศรที่จุดเริ่มต้นของเส้น.<br/>            อ่าน/เขียน [`LineArrowheadLength`](/slides/python-net/th/aspose.slides/linearrowheadlength). |
| [`end_arrowhead_length`](/slides/python-net/th/aspose.slides/ilineformat/end_arrowhead_length/) | คืนค่าหรือกำหนดความยาวหัวศรที่จุดสิ้นสุดของเส้น.<br/>            อ่าน/เขียน [`LineArrowheadLength`](/slides/python-net/th/aspose.slides/linearrowheadlength). |

## เมธอด

| Method | Description |
| :- | :- |
| [`equals(self, line_format)`](/slides/python-net/th/aspose.slides/ilineformat/equals/#ilineformat) | กำหนดว่าตัวอย่าง LineFormat สองตัวเท่ากันหรือไม่ |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/ilineformat/get_effective/#) | รับข้อมูลการจัดรูปแบบเส้นที่มีผลโดยนำการสืบทอดมาใช้ |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)