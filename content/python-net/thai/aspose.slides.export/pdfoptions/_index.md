---
title: PdfOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/pdfoptions/
---
## PdfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ PDF

**การสืบทอด:**[`PdfOptions`](/slides/python-net/th/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท PdfOptions เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/pdfoptions/__init__/#) | Default constructor. |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/pdfoptions/warning_callback/) | คืนค่า หรือกำหนดออบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/pdfoptions/progress_callback/) | แสดงออบเจกต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์.<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/pdfoptions/default_regular_font/) | คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ.<br/>            อ่าน/เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/pdfoptions/gradient_style/) | คืนค่า หรือกำหนดสไตล์ภาพของการไล่สี.<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/pdfoptions/skip_java_script_links/) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ.<br/>            อ่าน/เขียน **bool**. ค่าเริ่มต้นคือ **false** . |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/pdfoptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกการนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/pdfoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมลักษณะของออบเจกต์ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/pdfoptions/show_hidden_slides/) | ระบุว่าจะรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`text_compression`](/slides/python-net/th/aspose.slides.export/pdfoptions/text_compression/) | ระบุประเภทการบีบอัดที่ใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร.<br/>            อ่าน/เขียน [`PdfTextCompression`](/slides/python-net/th/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/th/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | ระบุว่าจะเลือกการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดเริ่มต้น) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่<br/>            หากตั้งค่าเป็น **bool**.true, สำหรับทุกภาพในพรีเซนเทชันจะเลือกอัลกอริทึมการบีบอัดที่เหมาะสมที่สุด, ซึ่งจะทำให้ขนาดของไฟล์ PDF ที่ได้มีขนาดเล็กลง.<br/>            การเลือกอัตราการบีบอัดภาพที่ดีที่สุดต้องใช้การคำนวณที่มากและใช้ RAM เพิ่มเติม, และตัวเลือกนี้มีค่าเริ่มต้นเป็น **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/th/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | กำหนดว่า Aspose.Slides จะฝังฟอนต์ทั่วไปสำหรับข้อความ ASCII (ช่วงรหัส 33..127) หรือไม่.<br/>            ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ.<br/>            รายการฟอนต์ทั่วไปรวมถึงฟอนต์พื้นฐาน 14 ตัวของ PDF และฟอนต์ที่ผู้ใช้ระบุเพิ่มเติม.<br/>            อ่าน/เขียน **bool**. |
| [`additional_common_font_families`](/slides/python-net/th/aspose.slides.export/pdfoptions/additional_common_font_families/) | คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนต์ฟาไมลีกที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นฟอนต์ทั่วไป.<br/>            อ่าน/เขียน **str**[]. |
| [`embed_full_fonts`](/slides/python-net/th/aspose.slides.export/pdfoptions/embed_full_fonts/) | กำหนดว่าจะฝังอักขระทั้งหมดของฟอนต์หรือเฉพาะส่วนที่ใช้.<br/>            อ่าน/เขียน **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/th/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | ระบุว่าข้อความควรแปลงเป็นบิทแมพและบันทึกเป็น PDF หรือไม่เมื่อฟอนต์ไม่รองรับการเน้นตัวหนา.<br/>            วิธีนี้อาจปรับปรุงคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางตัว.<br/>            อ่าน/เขียน **bool**. |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/pdfoptions/jpeg_quality/) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF.<br/>            อ่าน/เขียน **int**. |
| [`compliance`](/slides/python-net/th/aspose.slides.export/pdfoptions/compliance/) | ระดับการปฏิบัติตามที่ต้องการสำหรับ PDF ที่สร้างขึ้น.<br/>            อ่าน/เขียน [`PdfCompliance`](/slides/python-net/th/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/th/aspose.slides.export/pdfoptions/password/) | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF.<br/>            อ่าน/เขียน **str**. |
| [`access_permissions`](/slides/python-net/th/aspose.slides.export/pdfoptions/access_permissions/) | มีชุดของแฟล็กที่กำหนดสิทธิ์การเข้าถึงที่ควรให้เมื่อเอกสารถูกเปิดด้วยสิทธิ์ผู้ใช้<br/>            ดู [`PdfAccessPermissions`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/th/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | ตั้งค่าเป็น true เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในพรีเซนเทชันเป็นภาพ PNG.<br/>            อ่าน/เขียน **bool**. |
| [`sufficient_resolution`](/slides/python-net/th/aspose.slides.export/pdfoptions/sufficient_resolution/) | คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF.<br/>            <br/>คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของภาพ.<br/><br/><br/>ค่าเริ่มต้นคือ **96** .<br/><br/><br/>            อ่าน/เขียน **float**. |
| [`draw_slides_frame`](/slides/python-net/th/aspose.slides.export/pdfoptions/draw_slides_frame/) | ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์.<br/>             อ่าน/เขียน **bool**. |
| [`image_transparent_color`](/slides/python-net/th/aspose.slides.export/pdfoptions/image_transparent_color/) | รับหรือกำหนดสีโปร่งใสของรูปภาพ. |
| [`apply_image_transparent`](/slides/python-net/th/aspose.slides.export/pdfoptions/apply_image_transparent/) | ใช้สีโปร่งใสที่ระบุกับรูปภาพหาก `true`. |
| [`include_ole_data`](/slides/python-net/th/aspose.slides.export/pdfoptions/include_ole_data/) | ตั้งค่าเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากพรีเซนเทชันเป็นไฟล์ฝังใน PDF ที่ได้.<br/>            อ่าน/เขียน **bool**. |


### ดูเพิ่มเติม
* คลาส [`PdfOptions`](/slides/python-net/th/aspose.slides.export/pdfoptions)
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)