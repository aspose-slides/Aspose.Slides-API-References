---
title: InkActions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.ink/inkactions/
---
## InkActions คลาส

แสดงถึงรากของการกระทำแบบหมึก

**Inheritance:**[`InkActions`](/slides/python-net/th/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท InkActions เปิดเผยสมาชิกต่อไปนี้:

## Properties

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides.ink/inkactions/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides.ink/inkactions/placeholder/) | คืนค่าตัวแทนที่สำหรับ shape. คืนค่า None หาก shape ไม่มีตัวแทนที่.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides.ink/inkactions/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides.ink/inkactions/raw_frame/) | คืนค่า หรือ ตั้งค่าคุณสมบัติกรอบ shape ดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides.ink/inkactions/frame/) | คืนค่า หรือ ตั้งค่าคุณสมบัติกรอบ shape.<br/>           อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides.ink/inkactions/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides.ink/inkactions/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติผลกระทบ 3d สำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides.ink/inkactions/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides.ink/inkactions/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides.ink/inkactions/hyperlink_click/) | คืนค่า หรือ ตั้งค่าลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | คืนค่า หรือ ตั้งค่าลิงก์ที่กำหนดสำหรับการชี้เมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides.ink/inkactions/hyperlink_manager/) | คืนค่าตัวจัดการลิงก์.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides.ink/inkactions/hidden/) | กำหนดว่า shape ถูกซ่อนไว้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides.ink/inkactions/z_order_position/) | คืนตำแหน่งของ shape ในลำดับ z.<br/>            Shapes[0] คืน shape ที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides.ink/inkactions/connection_site_count/) | คืนจำนวนตำแหน่งเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides.ink/inkactions/rotation/) | คืนค่า หรือ ตั้งค่ามุมการหมุนของ shape ที่ระบุเป็นองศาบนแกน z<br/>            ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides.ink/inkactions/x/) | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides.ink/inkactions/y/) | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides.ink/inkactions/width/) | รับหรือกำหนดความกว้างของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides.ink/inkactions/height/) | รับหรือกำหนดความสูงของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides.ink/inkactions/black_white_mode/) | คุณสมบัติกำหนดว่ารูปร่างจะถูกแสดงในโหมดสีดำ-ขาวอย่างไร..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides.ink/inkactions/unique_id/) | คืนค่าตัวระบุภายในที่ใช้ในระดับการนำเสนอ ซึ่งมีวัตถุประสงค์สำหรับใช้โดยแอดอินหรือโค้ดอื่น.<br/>            เนื่องจากค่นี้สามารถถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, ไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides.ink/inkactions/office_interop_shape_id/) | คืนค่าตัวระบุที่เป็นเอกลักษณ์ระดับสไลด์ที่คงที่ตลอดอายุของ shape และให้ PowerPoint หรือโค้ด interop อ้างอิง shape อย่างเชื่อถือได้จากที่ใดก็ได้ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides.ink/inkactions/alternative_text/) | คืนค่า หรือ ตั้งค่าข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides.ink/inkactions/alternative_text_title/) | คืนค่า หรือ ตั้งค่าชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides.ink/inkactions/name/) | คืนค่า หรือ ตั้งชือของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างถ้าจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides.ink/inkactions/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative' option<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides.ink/inkactions/shape_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides.ink/inkactions/is_grouped/) | กำหนดว่า shape ถูกจัดเป็นกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides.ink/inkactions/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนต์หาก shape อยู่ในกลุ่ม. หากไม่อยู่คืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides.ink/inkactions/slide/) | คืนสไลด์พาเรนต์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides.ink/inkactions/presentation/) | คืนการนำเสนอพาเรนต์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides.ink/inkactions/graphical_object_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |

## Methods

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides.ink/inkactions/get_image/#) | คืนภาพย่อของ shape.<br/>            ใช้ชนิด ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | คืนภาพย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides.ink/inkactions/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ได้เป็น placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ตามที่กำหนด. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides.ink/inkactions/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จาก layout หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides.ink/inkactions/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวนจากเนื้อหาที่เรนเดอร์. |


### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`InkActions`](/slides/python-net/th/aspose.slides.ink/inkactions)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)