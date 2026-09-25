---
title: HtmlGenerator class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator คลาส

เครื่องสร้าง Html.

ประเภท HtmlGenerator เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_image_size/) | ส่งคืนขนาดภาพสไลด์.<br/>            อ่านอย่างเดียว [`SizeF`](/slides/python-net/th/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | ส่งคืนหน่วยที่ใช้ระบุขนาดภาพสไลด์.<br/>            อ่านอย่างเดียว [`SvgCoordinateUnit`](/slides/python-net/th/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | ส่งคืนรหัส css ของหน่วยที่ใช้ระบุขนาดภาพสไลด์.<br/>            อ่านอย่างเดียว **str**. |
| [`previous_slide_index`](/slides/python-net/th/aspose.slides.export/htmlgenerator/previous_slide_index/) | ส่งคืนดัชนีของสไลด์ที่เร็นเดอร์ก่อนหน้า หรือ -1 หากกำลังเร็นเดอร์สไลด์แรก.<br/>            อ่านอย่างเดียว **int**. |
| [`slide_index`](/slides/python-net/th/aspose.slides.export/htmlgenerator/slide_index/) | ส่งคืนดัชนีของสไลด์ที่กำลังเร็นเดอร์.<br/>            อ่านอย่างเดียว **int**. |
| [`next_slide_index`](/slides/python-net/th/aspose.slides.export/htmlgenerator/next_slide_index/) | ส่งคืนดัชนีของสไลด์ที่จะถูกเร็นเดอร์หลังจากสไลด์ปัจจุบัน หรือ -1 หากกำลังเร็นเดอร์สไลด์สุดท้าย.<br/>            อ่านอย่างเดียว **int**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_html/#str) | เพิ่มข้อความ HTML ที่จัดรูปแบบ. |
| [`add_html(self, html)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_html/#listchar) | เพิ่มข้อความ HTML ที่จัดรูปแบบ. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | เพิ่มข้อความ HTML ที่จัดรูปแบบ. |
| [`add_text(self, text)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_text/#str) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html.<br/>            การขึ้นบรรทัดใหม่และช่องว่างไม่ได้ถูกแทนที่. |
| [`add_text(self, text)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_text/#listchar) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html.<br/>            การขึ้นบรรทัดใหม่และช่องว่างไม่ได้ถูกแทนที่. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี html.<br/>            การขึ้นบรรทัดใหม่และช่องว่างไม่ได้ถูกแทนที่. |
| [`add_attribute_value(self, value)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html. |
| [`add_attribute_value(self, value)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/th/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | ใส่เครื่องหมายคำพูดให้ค่าคุณลักษณะและเพิ่มลงในไฟล์ html. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)