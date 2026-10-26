---
title: ISwfOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/iswfoptions/
---
## ISwfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็นรูปแบบ SWF

ประเภท ISwfOptions เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`compressed`](/slides/python-net/th/aspose.slides.export/iswfoptions/compressed/) | ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างหรือไม่<br/>            ค่าเริ่มต้นคือ `true`. |
| [`viewer_included`](/slides/python-net/th/aspose.slides.export/iswfoptions/viewer_included/) | ระบุว่าควรรวมตัวดูเอกสารในเอกสาร SWF ที่สร้างหรือไม่<br/>            ค่าเริ่มต้นคือ `true`. |
| [`show_page_border`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_page_border/) | ระบุว่าควรแสดงเส้นขอบรอบหน้าหรือไม่ ค่าเริ่มต้นคือ true. |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_hidden_slides/) | ระบุว่าควรรวมสไลด์ที่ซ่อนในเอกสารที่สร้างหรือไม่<br/>            ค่าเริ่มต้นคือ `false`. |
| [`show_full_screen`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_full_screen/) | แสดง/ซ่อนปุ่มเต็มหน้าจอ สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ true. |
| [`show_page_stepper`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_page_stepper/) | แสดง/ซ่อนตัวเปลี่ยนหน้า สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ true. |
| [`show_search`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_search/) | แสดง/ซ่อนส่วนค้นหา สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ true. |
| [`show_top_pane`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_top_pane/) | แสดง/ซ่อนแถบบนทั้งหมด สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ true. |
| [`show_bottom_pane`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_bottom_pane/) | แสดง/ซ่อนแถบล่าง สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ true. |
| [`show_left_pane`](/slides/python-net/th/aspose.slides.export/iswfoptions/show_left_pane/) | แสดง/ซ่อนแถบซ้าย สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ true. |
| [`start_open_left_pane`](/slides/python-net/th/aspose.slides.export/iswfoptions/start_open_left_pane/) | เริ่มต้นด้วยแถบซ้ายที่เปิดอยู่ สามารถกำหนดค่าแทนใน flashvars ค่าเริ่มต้นคือ false. |
| [`enable_context_menu`](/slides/python-net/th/aspose.slides.export/iswfoptions/enable_context_menu/) | เปิด/ปิดเมนูบริบท ค่าเริ่มต้นคือ true. |
| [`logo_image_bytes`](/slides/python-net/th/aspose.slides.export/iswfoptions/logo_image_bytes/) | ภาพที่จะแสดงเป็นโลโก้ที่มุมบนขวาของผู้ชม<br/>            ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| [`logo_link`](/slides/python-net/th/aspose.slides.export/iswfoptions/logo_link/) | รับหรือกำหนดที่อยู่อ้างอิงเต็มสำหรับโลโก้<br/>            มีผลเฉพาะเมื่อมีการระบุ [`ISwfOptions.logo_image_bytes`](/slides/python-net/th/aspose.slides.export/iswfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/iswfoptions/jpeg_quality/) | ระบุคุณภาพของภาพ JPEG<br/>            ค่าเริ่มต้นคือ 95. |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/iswfoptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์จะจัดวางบนหน้าเมื่อส่งออกการนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions)<br/>            คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจ็กต์ประเภท `Aspose.Slides.Export.HandoutLayoutingOptions` |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/iswfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/iswfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/iswfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/iswfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/iswfoptions/skip_java_script_links/) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)