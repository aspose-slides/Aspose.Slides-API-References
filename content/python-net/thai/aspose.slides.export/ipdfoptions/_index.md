---
title: IPdfOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/ipdfoptions/
---
## IPdfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการพรีเซนเทชันในรูปแบบ Pdf

ประเภท IPdfOptions เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`text_compression`](/slides/python-net/th/aspose.slides.export/ipdfoptions/text_compression/) | ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาแบบข้อความทั้งหมดในเอกสาร.<br/>            อ่าน/เขียน [`PdfTextCompression`](/slides/python-net/th/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/th/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | ระบุว่าต้องเลือกการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่<br/>            ถ้ากำหนดเป็น **bool**.true, สำหรับภาพแต่ละภาพในงานนำเสนอจะเลือกอัลกอริทึมการบีบอัดที่เหมาะสมที่สุด<br/>            ซึ่งจะทำให้ขนาด PDF ที่ได้เล็กลง.<br/>            การเลือกอัตราการบีบอัดภาพที่ดีที่สุดใช้ทรัพยากรการคำนวณสูงและต้องการ RAM เพิ่มเติม, และตัวเลือกนี้มีค่าเริ่มต้นเป็น **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/th/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | เป็นจริงเพื่อฝังฟอนต์ TrueType สำหรับอักขระ ASCII 32-127.<br/>            ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ.<br/>            อ่าน/เขียน **bool**. |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/ipdfoptions/show_hidden_slides/) | ระบุว่ากรณีเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`additional_common_font_families`](/slides/python-net/th/aspose.slides.export/ipdfoptions/additional_common_font_families/) | คืนค่าหรือกำหนดอาร์เรย์ของชื่อฟอนต์ฟาไมลีที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นทั่วไป.<br/>            อ่าน/เขียน **str**[]. |
| [`embed_full_fonts`](/slides/python-net/th/aspose.slides.export/ipdfoptions/embed_full_fonts/) | กำหนดว่าต้องฝังตัวอักษรทั้งหมดของฟอนต์หรือเพียงส่วนย่อยที่ใช้.<br/>            อ่าน/เขียน **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/th/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | ระบุว่าข้อความควรถูกเรสเตอร์ไทซ์เป็นบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการทำให้ตัวหนา.<br/>            วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางชนิด.<br/>            อ่าน/เขียน **bool**. |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/ipdfoptions/jpeg_quality/) | คืนค่าหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF.<br/>            อ่าน/เขียน **int**. |
| [`compliance`](/slides/python-net/th/aspose.slides.export/ipdfoptions/compliance/) | ระดับความสอดคล้องที่ต้องการสำหรับเอกสาร PDF ที่สร้าง.<br/>            อ่าน/เขียน [`PdfCompliance`](/slides/python-net/th/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/th/aspose.slides.export/ipdfoptions/password/) | ตั้งรหัสผ่านผู้ใช้เพื่อป้องกันเอกสาร PDF.<br/>            อ่าน/เขียน **str**. |
| [`access_permissions`](/slides/python-net/th/aspose.slides.export/ipdfoptions/access_permissions/) | มีชุดของแฟล็กที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดบ้างเมื่อเปิดเอกสารด้วยสิทธิ์ผู้ใช้.<br/>            ดู [`PdfAccessPermissions`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/th/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | เป็นจริงเพื่อแปลงเมทาฟายล์ทั้งหมดที่ใช้ในพรีเซนเทชันเป็นภาพ PNG.<br/>            อ่าน/เขียน **bool**. |
| [`sufficient_resolution`](/slides/python-net/th/aspose.slides.export/ipdfoptions/sufficient_resolution/) | คืนค่าหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF.<br/>            <br/>คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของภาพ.<br/><br/><br/>ค่าปริยายคือ **96** .<br/><br/><br/>            อ่าน/เขียน **float**. |
| [`draw_slides_frame`](/slides/python-net/th/aspose.slides.export/ipdfoptions/draw_slides_frame/) | เป็นจริงเพื่อวาดกรอบสีดำรอบแต่ละสไลด์.<br/>             อ่าน/เขียน **bool**. |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/ipdfoptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกพรีเซนเทชัน [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/th/aspose.slides.export/ipdfoptions/image_transparent_color/) | รับหรือกำหนดสีโปร่งใสของภาพ. |
| [`apply_image_transparent`](/slides/python-net/th/aspose.slides.export/ipdfoptions/apply_image_transparent/) | นำสีโปร่งใสที่ระบุไปใช้กับภาพหาก `true`. |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/ipdfoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/th/aspose.slides.export/ipdfoptions/include_ole_data/) | เป็นจริงเพื่อแปลงข้อมูล OLE ทั้งหมดจากพรีเซนเทชันเป็นไฟล์ฝังใน PDF ที่ได้.<br/>            อ่าน/เขียน **bool**. |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)