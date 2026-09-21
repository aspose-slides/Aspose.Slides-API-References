---
title: HtmlGenerator class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator คลาส

ตัวสร้าง Html.

ชนิด HtmlGenerator มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | รายละเอียด |
| :- | :- |
| [`slide_image_size`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_image_size/) | คืนขนาดภาพสไลด์.<br/>            อ่านอย่างเดียว **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | คืนหน่วยที่กำหนดขนาดภาพสไลด์.<br/>            อ่านอย่างเดียว [`SvgCoordinateUnit`](/slides/python-net/th/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | คืนรหัส css ของหน่วยที่กำหนดขนาดภาพสไลด์.<br/>            อ่านอย่างเดียว **str**. |
| [`previous_slide_index`](/slides/python-net/th/aspose.slides.export/htmlgenerator/previous_slide_index/) | คืนดัชนีของสไลด์ที่เรนเดอร์ก่อนหน้า หรือ -1 หากเป็นสไลด์แรกที่กำลังเรนเดอร์.<br/>            อ่านอย่างเดียว **int**. |
| [`slide_index`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_index/) | คืนดัชนีของสไลด์ที่กำลังเรนเดอร์อยู่.<br/>            อ่านอย่างเดียว **int**. |
| [`next_slide_index`](/slides/python-net/th/aspose.slides.export/htmlgenerator/next_slide_index/) | คืนดัชนีของสไลด์ที่จะเรนเดอร์หลังจากสไลด์ปัจจุบัน หรือ -1 หากกำลังเรนเดอร์สไลด์สุดท้ายอยู่.<br/>            อ่านอย่างเดียว **int**. |

## เมธอด

| เมธอด | รายละเอียด |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_html/#str) | เพิ่มข้อความ HTML ที่จัดรูปแบบ. |
| [`add_html(self, html)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_html/#listchar) | เพิ่มข้อความ HTML ที่จัดรูปแบบ. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | เพิ่มข้อความ HTML ที่จัดรูปแบบ. |
| [`add_text(self, text)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_text/#str) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย entities ของ html.<br/>            การขึ้นบรรทัดใหม่และช่องว่างไม่ถูกแทนที่. |
| [`add_text(self, text)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_text/#listchar) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย entities ของ html.<br/>            การขึ้นบรรทัดใหม่และช่องว่างไม่ถูกแทนที่. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย entities ของ html.<br/>            การขึ้นบรรทัดใหม่และช่องว่างไม่ถูกแทนที่. |
| [`add_attribute_value(self, value)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | ใส่เครื่องหมายคำพูดให้กับค่า attribute และเพิ่มลงในไฟล์ html. |
| [`add_attribute_value(self, value)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | ใส่เครื่องหมายคำพูดให้กับค่า attribute และเพิ่มลงในไฟล์ html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | ใส่เครื่องหมายคำพูดให้กับค่า attribute และเพิ่มลงในไฟล์ html. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)