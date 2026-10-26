---
title: Shape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shape/
---
## คลาส Shape

แสดงถึงรูปร่างบนสไลด์

ประเภท Shape มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/shape/is_text_holder/) | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/shape/placeholder/) | คืนค่าตัวแทนสำหรับรูปร่าง. คืนค่า None หากรูปร่างไม่มีตัวแทน.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/shape/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของรูปร่าง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/shape/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติของเฟรมรูปร่างดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/shape/frame/) | คืนค่า หรือกำหนดคุณสมบัติของเฟรมรูปร่าง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/shape/line_format/) | คืนค่าออปเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/shape/three_d_format/) | คืนค่าออปเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟ็กต์ 3 มิติสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/shape/effect_format/) | คืนค่าออปเจ็กต์ EffectFormat ซึ่งมีเอฟเฟ็กต์พิกเซลที่ใช้กับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติของเอฟเฟ็กต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/shape/fill_format/) | คืนค่าออปเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/shape/hyperlink_click/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/shape/hyperlink_mouse_over/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/shape/hyperlink_manager/) | คืนค่าตัวจัดการไฮเปอร์ลิงก์.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/shape/hidden/) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/shape/z_order_position/) | คืนค่าตำแหน่งของรูปร่างในลำดับ z.<br/>            Shapes[0] คืนค่ารูปร่างที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่อยู่ด้านหน้าของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/shape/connection_site_count/) | คืนค่าจำนวนตำแหน่งการเชื่อมต่อบนรูปร่าง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/shape/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบ<br/>            แกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/shape/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/shape/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/shape/width/) | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/shape/height/) | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/shape/black_white_mode/) | คุณสมบัติกำหนดว่ารูปร่างจะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id/) | คืนค่าอีดีของภายในที่มีขอบเขตการนำเสนอสำหรับใช้โดยส่วนเพิ่มเติมหรืโค้ดอื่น.<br/>            เนื่องจากค่าตัวนี้สามารถกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรมได้, จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id/) | คืนค่าอีดีที่มีขอบเขตสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างมั่นใจจากทุกตำแหน่งในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/shape/alternative_text/) | คืนค่า หรือกำหนดข้อความแทนที่เกี่ยวข้องกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/shape/alternative_text_title/) | คืนค่า หรือกำหนดหัวข้อของข้อความแทนที่ที่เกี่ยวข้องกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/shape/name/) | คืนค่า หรือกำหนดชื่อของรูปร่าง.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/shape/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/shape/shape_lock/) | คืนค่าการล็อกของรูปร่าง.<br/>            อ่านอย่างเดียว [`IBaseShapeLock`](/slides/python-net/th/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/shape/is_grouped/) | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/shape/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/shape/slide/) | คืนค่าสตไลด์พาเรนท์ของรูปร่าง.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/shape/presentation/) | คืนค่าการนำเสนอพาเรนท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/shape/get_image/#) | คืนค่าภาพย่อของรูปร่าง.<br/>            ใช้ชนิด ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของรูปร่าง. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของรูปร่าง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/shape/write_as_svg/#iorawiobase) | บันทึกเนื้อหา Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหา Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/shape/remove_placeholder/#) | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวแทน. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/shape/add_placeholder/#iplaceholder) | เพิ่มตัวแทนใหม่หากไม่มีและกำหนดคุณสมบัติตัวแทนให้กับที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/shape/get_base_placeholder/#) | คืนรูปร่างตัวแทนพื้นฐาน (รูปร่างจากการจัดวางและ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หากรูปร่างปัจจุบันไม่ได้รับการสืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/shape/get_visual_bounds/#) | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)