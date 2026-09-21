---
title: TiffOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/tiffoptions/
---
## TiffOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF

**Inheritance:**[`TiffOptions`](/slides/python-net/th/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท TiffOptions เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| ผู้สร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/tiffoptions/__init__/#) | ผู้สร้างเริ่มต้น. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/tiffoptions/warning_callback/) | ส่งคืนหรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/tiffoptions/progress_callback/) | แสดงอ็อบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์.<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/tiffoptions/default_regular_font/) | ส่งคืนหรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ.<br/>            อ่าน-เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/tiffoptions/gradient_style/) | ส่งคืนหรือกำหนดสไตล์การแสดงผลของไล่สี.<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/tiffoptions/skip_java_script_links/) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อตอนบันทึกงานนำเสนอ.<br/>            อ่าน/เขียน **bool**. ค่าปริยายคือ **false**. |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/tiffoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/tiffoptions/show_hidden_slides/) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่.<br/>            ค่าปริยายคือ `false`. |
| [`image_size`](/slides/python-net/th/aspose.slides.export/tiffoptions/image_size/) | ระบุขนาดของภาพ TIFF ที่สร้าง.<br/>            ค่าปริยายคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะคำนวณตามค่าขนาดสไลด์ของงานนำเสนอ.<br/>            อ่าน/เขียน **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/th/aspose.slides.export/tiffoptions/dpi_x/) | ระบุความละเอียดตามแนวนอนเป็นจุดต่อนิ้ว.<br/>            อ่าน/เขียน **int**. |
| [`dpi_y`](/slides/python-net/th/aspose.slides.export/tiffoptions/dpi_y/) | ระบุความละเอียดตามแนวตั้งเป็นจุดต่อนิ้ว.<br/>            อ่าน/เขียน **int**. |
| [`compression_type`](/slides/python-net/th/aspose.slides.export/tiffoptions/compression_type/) | ระบุประเภทการบีบอัด.<br/>            อ่าน/เขียน [`TiffCompressionTypes`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/th/aspose.slides.export/tiffoptions/pixel_format/) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง.<br/>            อ่าน/เขียน [`ImagePixelFormat`](/slides/python-net/th/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/tiffoptions/slides_layout_options/) | ส่งคืนหรือกำหนดโหมดที่สไลด์จะวางบนหน้ากระดาษเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/th/aspose.slides.export/tiffoptions/bw_conversion_mode/) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาว-ดำ.<br/>            ตัวเลือกนี้จะถูกนำไปใช้เฉพาะเมื่อ [`TiffOptions.compression_type`](/slides/python-net/th/aspose.slides.export/tiffoptions/compression_type) <br/>            ถูกตั้งค่าเป็น [`TiffCompressionTypes.CCITT4`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes/CCITT4) หรือ [`TiffCompressionTypes.CCITT3`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            อ่าน/เขียน [`BlackWhiteConversionMode`](/slides/python-net/th/aspose.slides.export/blackwhiteconversionmode).<br/>            ค่าปริยายคือ [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/th/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### ดูเพิ่มเติม
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* คลาส [`TiffOptions`](/slides/python-net/th/aspose.slides.export/tiffoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)