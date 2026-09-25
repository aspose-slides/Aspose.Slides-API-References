---
title: TiffOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/tiffoptions/
---
## TiffOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF.

**การสืบทอด:**[`TiffOptions`](/slides/python-net/th/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท TiffOptions เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/tiffoptions/__init__/#) | ตัวสร้างเริ่มต้น. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/tiffoptions/warning_callback/) | คืนหรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือหยุดทำงาน.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/tiffoptions/progress_callback/) | แสดงอ็อบเจกต์ callback สำหรับบันทึกการอัพเดตความคืบหน้าเป็นเปอร์เซ็นต์.<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/tiffoptions/default_regular_font/) | คืนหรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง.<br/>            อ่าน/เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/tiffoptions/gradient_style/) | คืนหรือกำหนดสไตล์การแสดงผลของ gradient.<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/tiffoptions/skip_java_script_links/) | ระบุว่าจะข้าม hyperlink ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ.<br/>            อ่าน/เขียน **bool**. ค่าเริ่มต้นคือ **false** . |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/tiffoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/tiffoptions/show_hidden_slides/) | ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`image_size`](/slides/python-net/th/aspose.slides.export/tiffoptions/image_size/) | ระบุขนาดของภาพ TIFF ที่สร้าง.<br/>            ค่าตั้งต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างจะคำนวณตามค่าขนาดสไลด์ของงานนำเสนอ.<br/>            อ่าน/เขียน [`Size`](/slides/python-net/th/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/th/aspose.slides.export/tiffoptions/dpi_x/) | ระบุความละเอียดแนวนอนเป็น dot ต่อ นิ้ว.<br/>            อ่าน/เขียน **int**. |
| [`dpi_y`](/slides/python-net/th/aspose.slides.export/tiffoptions/dpi_y/) | ระบุความละเอียดแนวตั้งเป็น dot ต่อ นิ้ว.<br/>            อ่าน/เขียน **int**. |
| [`compression_type`](/slides/python-net/th/aspose.slides.export/tiffoptions/compression_type/) | ระบุประเภทการบีบอัด.<br/>            อ่าน/เขียน [`TiffCompressionTypes`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/th/aspose.slides.export/tiffoptions/pixel_format/) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง.<br/>            อ่าน/เขียน [`ImagePixelFormat`](/slides/python-net/th/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/tiffoptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/th/aspose.slides.export/tiffoptions/bw_conversion_mode/) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ.<br/>            ตัวเลือกนี้จะใช้เฉพาะเมื่อ [`TiffOptions.compression_type`](/slides/python-net/th/aspose.slides.export/tiffoptions/compression_type) <br/>            ถูกตั้งค่าเป็น [`TiffCompressionTypes.CCITT4`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes/CCITT4) หรือ [`TiffCompressionTypes.CCITT3`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            อ่าน/เขียน [`BlackWhiteConversionMode`](/slides/python-net/th/aspose.slides.export/blackwhiteconversionmode).<br/>            ค่าเริ่มต้นคือ [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/th/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### ดูเพิ่มเติม
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* คลาส [`TiffOptions`](/slides/python-net/th/aspose.slides.export/tiffoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)