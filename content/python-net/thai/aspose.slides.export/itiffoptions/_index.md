---
title: ITiffOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/itiffoptions/
---
## คลาส ITiffOptions

Provides options that control how a presentation is saved in TIFF format.

The ITiffOptions type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/th/aspose.slides.export/itiffoptions/image_size/) | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น.<br/>            ค่าเริ่มต้นคือ 0x0, ซึ่งหมายความว่าขนาดภาพที่สร้างจะถูกคำนวณตามขนาดสไลด์ของงานนำเสนอ.<br/>            อ่าน/เขียน [`Size`](/slides/python-net/th/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/th/aspose.slides.export/itiffoptions/dpi_x/) | ระบุความละเอียดในแนวนอนเป็นจุดต่อดอทต่ออินช์.<br/>            อ่าน/เขียน **int**. |
| [`dpi_y`](/slides/python-net/th/aspose.slides.export/itiffoptions/dpi_y/) | ระบุความละเอียดในแนวตั้งเป็นจุดต่อดอทต่ออินช์.<br/>            อ่าน/เขียน **int**. |
| [`show_hidden_slides`](/slides/python-net/th/aspose.slides.export/itiffoptions/show_hidden_slides/) | ระบุว่าด큐เมนต์ที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่.<br/>            ค่าเริ่มต้นคือ `false`. |
| [`compression_type`](/slides/python-net/th/aspose.slides.export/itiffoptions/compression_type/) | ระบุประเภทการบีบอัด.<br/>            อ่าน/เขียน [`TiffCompressionTypes`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/th/aspose.slides.export/itiffoptions/pixel_format/) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น.<br/>            อ่าน/เขียน [`ImagePixelFormat`](/slides/python-net/th/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/th/aspose.slides.export/itiffoptions/slides_layout_options/) | รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](/slides/python-net/th/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/th/aspose.slides.export/itiffoptions/bw_conversion_mode/) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพสีขาว-ดำ.<br/>            ตัวเลือกนี้จะใช้เฉพาะเมื่อ [`ITiffOptions.compression_type`](/slides/python-net/th/aspose.slides.export/itiffoptions/compression_type) <br/>            ตั้งเป็น [`TiffCompressionTypes.CCITT4`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes/CCITT4) หรือ [`TiffCompressionTypes.CCITT3`](/slides/python-net/th/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            อ่าน/เขียน [`BlackWhiteConversionMode`](/slides/python-net/th/aspose.slides.export/blackwhiteconversionmode).<br/>            ค่าเริ่มต้นคือ [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/th/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/itiffoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก.<br/>            อ่าน-อย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)