---
title: HtmlOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/htmloptions/
---
## HtmlOptions คลาส

แสดงถึงตัวเลือกการส่งออก HTML.

**Inheritance:**[`HtmlOptions`](/slides/python-net/th/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท HtmlOptions เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/th/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | สร้างวัตถุ HtmlOptions ใหม่โดยระบุ callback. |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/htmloptions/__init__/#) | สร้างวัตถุ HtmlOptions ใหม่สำหรับบันทึกเป็นไฟล์ HTML เดียว. |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/htmloptions/warning_callback/) | รับหรือกำหนดวัตถุที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อไปหรือจะถูกยกเลิก.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/htmloptions/progress_callback/) | แสดงวัตถุ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์.<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/htmloptions/default_regular_font/) | รับหรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง.<br/>            อ่าน-เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/htmloptions/gradient_style/) | รับหรือกำหนดสไตล์การแสดงผลของการไล่สี.<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/htmloptions/skip_java_script_links/) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript หรือไม่เมื่อบันทึกการนำเสนอ.<br/>            อ่าน/เขียน **bool**. ค่าเริ่มต้นคือ **false**. |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/htmloptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้ากระดาษเมื่อส่งออกการนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/htmloptions/ink_options/) | ระบุทางเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/htmloptions/show_hidden_slides/) | ระบุว่าหมวดเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`html_formatter`](/slides/python-net/th/aspose.slides.export/htmloptions/html_formatter/) | รับหรือกำหนดเทมเพลต HTML.<br/>            อ่าน/เขียน [`IHtmlFormatter`](/slides/python-net/th/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/th/aspose.slides.export/htmloptions/disable_font_ligatures/) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures หรือไม่.<br/>            เมื่อกำหนดเป็น `true` ligatures จะถูกปิดในผลลัพธ์ที่เรนเดอร์. โดยค่าเริ่มต้น คุณสมบัตินี้ตั้งเป็น `false`. |
| [`slide_image_format`](/slides/python-net/th/aspose.slides.export/htmloptions/slide_image_format/) | รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์.<br/>            อ่าน/เขียน [`ISlideImageFormat`](/slides/python-net/th/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/htmloptions/jpeg_quality/) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF.<br/>            อ่าน/เขียน **int**. |
| [`pictures_compression`](/slides/python-net/th/aspose.slides.export/htmloptions/pictures_compression/) | แสดงระดับการบีบอัดของรูปภาพ |
| [`delete_pictures_cropped_areas`](/slides/python-net/th/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | แฟล็กบูลีนบอกว่าตำแหน่งที่ถูกตัดออกจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true ส่วนที่ถูกตัด <br/>            จะถูกลบ, หากเป็น false จะถูกบันทึกในเอกสาร (ซึ่งอาจทำให้ไฟล์มีขนาดใหญ่ขึ้น) |
| [`svg_responsive_layout`](/slides/python-net/th/aspose.slides.export/htmloptions/svg_responsive_layout/) | True เพื่อไม่รวมแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ svg - จะทำให้การจัดวางเป็นแบบตอบสนอง. False - ในกรณีอื่น.<br/>            อ่าน/เขียน **bool**. |

### ดูเพิ่ม
* คลาส [`HtmlOptions`](/slides/python-net/th/aspose.slides.export/htmloptions)
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)