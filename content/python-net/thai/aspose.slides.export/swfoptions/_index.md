---
title: SwfOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/swfoptions/
---
## SwfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ Swf.

**การสืบทอด:**[`SwfOptions`](/slides/python-net/th/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท SwfOptions เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/swfoptions/__init__/#) | คอนสตรัคเตอร์เริ่มต้น. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/swfoptions/warning_callback/) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/swfoptions/progress_callback/) | เป็นอ็อบเจกต์ callback สำหรับการอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์.<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/swfoptions/default_regular_font/) | คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง.<br/>            อ่าน-เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/swfoptions/gradient_style/) | คืนค่า หรือกำหนดรูปแบบการแสดงผลของการไล่สี.<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/swfoptions/skip_java_script_links/) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ.<br/>            อ่าน/เขียน **bool**. ค่าเริ่มต้นคือ **false** . |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/swfoptions/show_hidden_slides/) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`compressed`](/slides/python-net/th/aspose.slides.export/swfoptions/compressed/) | ระบุว่าเอกสาร SWF ที่สร้างควรถูกบีบอัดหรือไม่.<br/>            ค่าเริ่มต้นคือ `true`. |
| [`viewer_included`](/slides/python-net/th/aspose.slides.export/swfoptions/viewer_included/) | ระบุว่าเอกสาร SWF ที่สร้างควรรวมตัวดูเอกสารแบบบูรณาการหรือไม่.<br/>            ค่าเริ่มต้นคือ `true`. |
| [`show_page_border`](/slides/python-net/th/aspose.slides.export/swfoptions/show_page_border/) | ระบุว่าขอบรอบหน้าควรแสดงหรือไม่. ค่าเริ่มต้นคือ true. |
| [`show_full_screen`](/slides/python-net/th/aspose.slides.export/swfoptions/show_full_screen/) | แสดง/ซ่อนปุ่มเต็มจอ. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true. |
| [`show_page_stepper`](/slides/python-net/th/aspose.slides.export/swfoptions/show_page_stepper/) | แสดง/ซ่อนตัวควบคุมหน้า. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true. |
| [`show_search`](/slides/python-net/th/aspose.slides.export/swfoptions/show_search/) | แสดง/ซ่อนส่วนค้นหา. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true. |
| [`show_top_pane`](/slides/python-net/th/aspose.slides.export/swfoptions/show_top_pane/) | แสดง/ซ่อนแผงบนทั้งหมด. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true. |
| [`show_bottom_pane`](/slides/python-net/th/aspose.slides.export/swfoptions/show_bottom_pane/) | แสดง/ซ่อนแผงล่าง. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true. |
| [`show_left_pane`](/slides/python-net/th/aspose.slides.export/swfoptions/show_left_pane/) | แสดง/ซ่อนแผงซ้าย. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true. |
| [`start_open_left_pane`](/slides/python-net/th/aspose.slides.export/swfoptions/start_open_left_pane/) | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ false. |
| [`enable_context_menu`](/slides/python-net/th/aspose.slides.export/swfoptions/enable_context_menu/) | เปิด/ปิดเมนูบริบท. ค่าเริ่มต้นคือ true. |
| [`logo_image_bytes`](/slides/python-net/th/aspose.slides.export/swfoptions/logo_image_bytes/) | ภาพที่จะแสดงเป็นโลโก้ในมุมบนขวาของตัวดู.<br/>            ภาพควรเป็น PNG ขนาด 32x64 พิกเซล, หากไม่เช่นนั้นอาจทำให้โลโก้แสดงไม่ถูกต้อง. |
| [`logo_link`](/slides/python-net/th/aspose.slides.export/swfoptions/logo_link/) | รับหรือกำหนดที่อยู่อินเทอร์เน็ตแบบเต็มสำหรับโลโก้.<br/>            มีผลเฉพาะเมื่อมีการระบุ [`SwfOptions.logo_image_bytes`](/slides/python-net/th/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/swfoptions/jpeg_quality/) | ระบุคุณภาพของภาพ JPEG.<br/>            ค่าเริ่มต้นคือ 95. |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/swfoptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกการนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions).<br/>            คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ประเภท [`HandoutLayoutingOptions`](/slides/python-net/th/aspose.slides.export/handoutlayoutingoptions) |

### ดูเพิ่มเติม
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* คลาส [`SwfOptions`](/slides/python-net/th/aspose.slides.export/swfoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)