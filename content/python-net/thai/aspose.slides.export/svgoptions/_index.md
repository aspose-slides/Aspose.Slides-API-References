---
title: SVGOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/svgoptions/
---
## SVGOptions คลาส

เป็นตัวเลือกของ SVG.

**สืบทอด:**[`SVGOptions`](/slides/python-net/th/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)

ประเภท SVGOptions แสดงสมาชิกต่อไปนี้:

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.export/svgoptions/__init__/#) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions |
| [`__init__(self, link_embed_controller)`](/slides/python-net/th/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions โดยระบุอ็อบเจ็กต์ตัวควบคุมการฝังลิงก์ |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/svgoptions/warning_callback/) | คืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/svgoptions/progress_callback/) | เป็นอ็อบเจ็กต์คอลแบ็คสำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์<br/>            ดู [`IProgressCallback`](/slides/python-net/th/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/svgoptions/default_regular_font/) | คืนหรือกำหนดฟอนต์ที่ใช้เมื่อไม่พบฟอนต์ต้นฉบับ<br/>            อ่าน/เขียน **str**. |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/svgoptions/gradient_style/) | คืนหรือกำหนดสไตล์ภาพของกราเดียนท์<br/>            อ่าน/เขียน [`GradientStyle`](/slides/python-net/th/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/svgoptions/skip_java_script_links/) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อต้องบันทึกการนำเสนอ<br/>            อ่าน/เขียน **bool**. ค่าเริ่มต้นคือ **false** . |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/svgoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/th/aspose.slides.export/svgoptions/use_frame_size/) | กำหนดว่ากรอบข้อความจะรวมอยู่ในพื้นที่เรนเดอร์หรือไม่<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้นคือ false. |
| [`use_frame_rotation`](/slides/python-net/th/aspose.slides.export/svgoptions/use_frame_rotation/) | กำหนดว่าจะทำการหมุนตามที่ระบุของรูปทรงเมื่อเรนเดอร์หรือไม่<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้นคือ true. |
| [`vectorize_text`](/slides/python-net/th/aspose.slides.export/svgoptions/vectorize_text/) | กำหนดว่าข้อความบนสไลด์จะบันทึกเป็นกราฟิกหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/th/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | คืนหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไลซ์เมตาไฟล์<br/>            อ่าน/เขียน **int**. |
| [`disable_3d_text`](/slides/python-net/th/aspose.slides.export/svgoptions/disable_3d_text/) | กำหนดว่าข้อความ 3D จะปิดการทำงานใน SVG หรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`disable_gradient_split`](/slides/python-net/th/aspose.slides.export/svgoptions/disable_gradient_split/) | ปิดการแยกกราเดียนท์ FromCornerX และ FromCenter<br/>            อ่าน/เขียน **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/th/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 ขาดความสามารถในการกำหนดช่องว่างสำหรับมาร์คเกอร์<br/>            เครื่องมือเขียน SVG ของ Aspose.Slides มีวิธีแก้ปัญหานี้:<br/>            มันทำการครอปส่วนท้ายของเส้นที่มีลูกศร ทำให้เส้นไม่ทับมาร์คเกอร์<br/>            ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว<br/>            อ่าน/เขียน **bool**. |
| [`default`](/slides/python-net/th/aspose.slides.export/svgoptions/default/) | คืนค่าการตั้งค่าเริ่มต้น<br/>            อ่านอย่างเดียว [`SVGOptions`](/slides/python-net/th/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/th/aspose.slides.export/svgoptions/simple/) | คืนค่าการตั้งค่าการสร้างไฟล์ SVG ที่ง่ายที่สุดและเล็กที่สุด<br/>            อ่านอย่างเดียว [`SVGOptions`](/slides/python-net/th/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/th/aspose.slides.export/svgoptions/wysiwyg/) | คืนค่าการตั้งค่าการสร้างไฟล์ SVG ที่แม่นยำที่สุด<br/>            อ่านอย่างเดียว [`SVGOptions`](/slides/python-net/th/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/svgoptions/jpeg_quality/) | กำหนดคุณภาพการเข้ารหัส JPEG<br/>            อ่าน/เขียน **int**. |
| [`shape_formatting_controller`](/slides/python-net/th/aspose.slides.export/svgoptions/shape_formatting_controller/) | คืนและกำหนดอินเทอร์เฟซคอลแบ็คที่ให้ผู้ใช้ควบคุมการแปลงรูปทรง<br/>            อ่าน/เขียน [`ISvgShapeFormattingController`](/slides/python-net/th/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/th/aspose.slides.export/svgoptions/pictures_compression/) | เป็นระดับการบีบอัดรูปภาพ |
| [`delete_pictures_cropped_areas`](/slides/python-net/th/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | ฟลักบูลีนที่ระบุว่ามีส่วนที่ถูกครอปคงเหลือเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็นจริง ส่วนที่ถูกครอปจะถูกลบ หากเป็นเท็จจะถูกซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) |
| [`external_fonts_handling`](/slides/python-net/th/aspose.slides.export/svgoptions/external_fonts_handling/) | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก<br/>            อ่าน/เขียน [`SvgExternalFontsHandling`](/slides/python-net/th/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/th/aspose.slides.export/svgoptions/disable_font_ligatures/) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิกเจอร์<br/>            เมื่อกำหนดเป็น `true` ลิกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น `false`. |


### ดูเพิ่มเติม
* คลาส [`SaveOptions`](/slides/python-net/th/aspose.slides.export/saveoptions)
* คลาส [`SVGOptions`](/slides/python-net/th/aspose.slides.export/svgoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)