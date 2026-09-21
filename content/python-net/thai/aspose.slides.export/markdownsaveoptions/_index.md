---
title: MarkdownSaveOptions class
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions คลาส

แสดงถึงตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็น markdown.

**การสืบทอด:**[`MarkdownSaveOptions`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท MarkdownSaveOptions เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/__init__/#) | ตัวสร้าง. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/warning_callback/) | คืนค่าหรือกำหนดวัตถุที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/progress_callback/) | แสดงถึงวัตถุ callback สำหรับบันทึกการอัพเดตความคืบหน้าในเปอร์เซ็นต์.<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/default_regular_font/) | คืนค่าหรือกำหนดแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง.<br/>            อ่าน-เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/gradient_style/) | คืนค่าหรือกำหนดลักษณะภาพของการไล่ระดับสี.<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | ระบุว่าจะข้ามลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อลบงานนำเสนอ.<br/>            อ่าน/เขียน **bool**. ค่าเริ่มต้นคือ **false** . |
| [`export_type`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/export_type/) | ระบุสเปค markdown เพื่อแปลงงานนำเสนอ.<br/>            ค่าเริ่มต้นคือ `TextOnly`. |
| [`base_path`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/base_path/) | ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก.<br/>            ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน. |
| [`images_save_folder_name`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ.<br/>            ค่าเริ่มต้นคือ `Images`. |
| [`new_line_type`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/new_line_type/) | ระบุว่าจะให้เอกสารที่สร้างมีบรรทัดใหม่ \\r(Macintosh) \\n(Unix) หรือ \\r\\n(Windows) หรือไม่.<br/>            ค่าเริ่มต้นคือ `Unix`. |
| [`show_comments`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/show_comments/) | ระบุว่าจะให้เอกสารที่สร้างแสดงคอมเมนต์หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | ระบุว่าจะให้เอกสารที่สร้างรวมสไลด์ที่ซ่อนอยู่หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`show_slide_number`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/show_slide_number/) | ระบุว่าจะให้เอกสารที่สร้างแสดงหมายเลขของแต่ละสไลด์หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`flavor`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/flavor/) | ระบุสเปค markdown เพื่อแปลงงานนำเสนอ.<br/>            ค่าเริ่มต้นคือ `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/slide_number_format/) | รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับส่วนหัวหมายเลขสไลด์ในผลลัพธ์ Markdown.<br/>            รูปแบบต้องรวมตัวแทน \"{0}\" ซึ่งจะถูกแทนที่ด้วยดัชนีสไลด์ระหว่างการส่งออก.<br/>            ตัวอย่าง: \"# Slide {0}\" จะให้ผลลัพธ์เป็น \"# Slide 1\", \"# Slide 2\", เป็นต้น. |
| [`handle_repeated_spaces`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | หากตั้งค่าเป็น `true` จะลบบรรทัดที่ว่างเปล่าหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown สุดท้าย.<br/>            ค่าเริ่มต้นคือ `false`. |

### ดูเพิ่มเติม
* คลาส [`MarkdownSaveOptions`](/slides/python-net/th/aspose.slides.export/markdownsaveoptions)
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)