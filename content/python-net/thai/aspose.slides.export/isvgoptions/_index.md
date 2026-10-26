---
title: ISVGOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/isvgoptions/
---
## ISVGOptions คลาส

เป็นตัวเลือกของ SVG.

The ISSVGOptions type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`vectorize_text`](/slides/python-net/th/aspose.slides.export/isvgoptions/vectorize_text/) | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/th/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | คืนค่า หรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟายล์.<br/>            อ่าน/เขียน **int**. |
| [`disable_3d_text`](/slides/python-net/th/aspose.slides.export/isvgoptions/disable_3d_text/) | กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`disable_gradient_split`](/slides/python-net/th/aspose.slides.export/isvgoptions/disable_gradient_split/) | ปิดการแยก Gradient FromCornerX และ FromCenter.<br/>            อ่าน/เขียน **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/th/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 ขาดความสามารถในการกำหนด inset สำหรับเครื่องหมาย.<br/>            เครื่องมือเขียน SVG ของ Aspose.Slides มีวิธีแก้ปัญหานี้:<br/>            มันทำการครอบส่วนปลายของเส้นที่มีลูกศร, ดังนั้น เส้นจะไม่ทับเครื่องหมาย.<br/>            ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว.<br/>            อ่าน/เขียน **bool**. |
| [`jpeg_quality`](/slides/python-net/th/aspose.slides.export/isvgoptions/jpeg_quality/) | กำหนดคุณภาพการเข้ารหัส JPEG.<br/>            อ่าน/เขียน **int**. |
| [`shape_formatting_controller`](/slides/python-net/th/aspose.slides.export/isvgoptions/shape_formatting_controller/) | คืนค่าและกำหนดอินเทอร์เฟซ callback ที่อนุญาตให้ผู้ใช้ควบคุมการแปลง shape.<br/>            อ่าน/เขียน [`ISvgShapeFormattingController`](/slides/python-net/th/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/th/aspose.slides.export/isvgoptions/pictures_compression/) | แสดงระดับการบีบอัดของรูปภาพ<br/>            อ่าน/เขียน [`ISVGOptions.pictures_compression`](/slides/python-net/th/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/th/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | แฟล็ก boolean ระบุว่าพาร์ทที่ถูกตัดทอนจะคงอยู่เป็นส่วนของเอกสารหรือไม่. หากเป็น true พาร์ทที่ตัดจะถูกลบ, หากเป็น false พวกมันจะถูก serialize ไว้ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)<br/>            อ่าน/เขียน **bool**. |
| [`use_frame_size`](/slides/python-net/th/aspose.slides.export/isvgoptions/use_frame_size/) | กำหนดว่าจะรวมกรอบข้อความไว้ในพื้นที่การเรนเดอร์หรือไม่.<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้นคือ false. |
| [`use_frame_rotation`](/slides/python-net/th/aspose.slides.export/isvgoptions/use_frame_rotation/) | กำหนดว่าจะทำการหมุนที่ระบุของ shape ขณะเรนเดอร์หรือไม่.<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้นคือ true. |
| [`external_fonts_handling`](/slides/python-net/th/aspose.slides.export/isvgoptions/external_fonts_handling/) | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก.<br/>            อ่าน/เขียน [`SvgExternalFontsHandling`](/slides/python-net/th/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/th/aspose.slides.export/isvgoptions/ink_options/) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก.<br/>            อ่านอย่างเดียว [`IInkOptions`](/slides/python-net/th/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/th/aspose.slides.export/isvgoptions/disable_font_ligatures/) | คืนค่า หรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ ligatures.<br/>            เมื่อกำหนดเป็น `true`, ligatures จะถูกปิดในผลลัพธ์ที่เรนเดอร์. ตามค่าเริ่มต้น, คุณลักษณะนี้ตั้งค่าเป็น `false`. |
| [`warning_callback`](/slides/python-net/th/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/th/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/th/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/th/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/th/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)