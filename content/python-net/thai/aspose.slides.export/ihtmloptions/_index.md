---
title: IHtmlOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions คลาส

แสดงถึงตัวเลือกการส่งออก HTML.

ประเภท IHtmlOptions มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`html_formatter`](/slides/python-net/th/aspose.slides.export/ihtmloptions/html_formatter/) | คืนค่า หรือกำหนด HTML template.<br/>            อ่าน/เขียน [`IHtmlFormatter`](/slides/python-net/th/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/th/aspose.slides.export/ihtmloptions/slide_image_format/) | คืนค่า หรือกำหนด slide image format options.<br/>            อ่าน/เขียน [`ISlideImageFormat`](/slides/python-net/th/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/ihtmloptions/show_hidden_slides/) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/ihtmloptions/jpeg_quality/) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF.<br/>            อ่าน/เขียน **int**. |
| [`pictures_compression`](/slides/python-net/th/aspose.slides.export/ihtmloptions/pictures_compression/) | แสดงระดับการบีบอัดรูปภาพ<br/>            อ่าน/เขียน [`IHtmlOptions.pictures_compression`](/slides/python-net/th/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/th/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | แฟล็กแบบบูลีนระบุว่าพาร์ทที่ตัดออกยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่. หาก true พาร์ทที่ตัดออกจะถูกลบ, หาก false จะถูกจัดซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)<br/>            อ่าน/เขียน **bool**. |
| [`svg_responsive_layout`](/slides/python-net/th/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | ตั้งเป็น true เพื่อไม่รวมแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - จะทำให้การจัดวางตอบสนองต่อขนาดหน้าจอ. ตั้งเป็น false ในกรณีอื่น.<br/>            อ่าน/เขียน **bool**. |
| [`disable_font_ligatures`](/slides/python-net/th/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลิการเจอร์.<br/>            เมื่อกำหนดเป็น `true` ลิการเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดง. ค่าเริ่มต้นของคุณสมบัตินี้คือ `false`. |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/ihtmloptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/ihtmloptions/ink_options/) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)