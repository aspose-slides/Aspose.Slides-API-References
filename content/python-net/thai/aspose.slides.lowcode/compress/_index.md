---
title: Compress class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.lowcode/compress/
---
## Compress คลาส

เป็นตัวแทนของกลุ่มของเมธอดที่มีจุดประสงค์เพื่อบีบอัด [`Presentation`](/slides/python-net/th/aspose.slides/presentation).

ประเภท Compress เปิดเผยสมาชิกต่อไปนี้:

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/th/aspose.slides.lowcode/compress/compress_presentation/#presentation) | ลดขนาดของงานนำเสนอโดยใช้ขั้นตอนการบีบอัดทั้งหมดที่มีอยู่:<br/>            <br/>* ลบสไลด์แม่แบบที่ไม่ได้ใช้ **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* ลบสไลด์เค้าโครงที่ไม่ได้ใช้ **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* เก็บเฉพาะ glyphs ที่ใช้จริงในฟอนท์ที่ฝังไว้ **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* ลดความละเอียดของรูปภาพเป็น 150 DPI และลบพื้นที่ที่ถูกครอบของรูปภาพ **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/th/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | ทำการบีบอัดของ [`Presentation`](/slides/python-net/th/aspose.slides/presentation) โดยการลบสไลด์แม่แบบที่ไม่ได้ใช้. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/th/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | ทำการบีบอัดของ [`Presentation`](/slides/python-net/th/aspose.slides/presentation) โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/th/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | ทำการบีบอัดของ [`Presentation`](/slides/python-net/th/aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนท์ที่ฝังไว้. |
| [`compress_images(presentation, resolution)`](/slides/python-net/th/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | ลดความละเอียดของรูปภาพในงานนำเสนอและลบพื้นที่ที่ถูกครอบของพวกมัน,<br/>            คล้ายกับฟีเจอร์ "Compress Pictures" ของ PowerPoint ที่ใช้กับรูปภาพทั้งหมด.<br/>            รูปภาพบนสไลด์, สไลด์เค้าโครงและสไลด์แม่แบบจะถูกประมวลผล, รวมถึงรูปภาพภายในกลุ่มรูปร่าง<br/>            และการเติมรูปภาพของรูปร่าง. |

### ดูเพิ่มเติม
* class [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)