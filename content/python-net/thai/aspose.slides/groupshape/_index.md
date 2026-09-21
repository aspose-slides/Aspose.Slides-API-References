---
title: GroupShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/groupshape/
---
## คลาส GroupShape

แทนกลุ่มของรูปทรงบนสไลด์

**การสืบทอด:**[`GroupShape`](/slides/python-net/th/aspose.slides/groupshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท GroupShape เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/groupshape/is_text_holder/) | กำหนดว่ารูปทรงเป็น TextHolder_PPT.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/groupshape/placeholder/) | คืนค่า placeholder สำหรับรูปทรง คืนค่า None หากรูปทรงไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/groupshape/custom_data/) | คืนค่าข้อมูลกำหนดเองของรูปทรง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/groupshape/raw_frame/) | คืนค่าหรือกำหนดคุณสมบัติของ raw shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/groupshape/frame/) | คืนค่าหรือกำหนดคุณสมบัติของ shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/groupshape/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปเส้นสำหรับรูปทรง.<br/>            หมายเหตุ: คืนค่า None สำหรับอ็อบเจ็กต์ GroupShape เนื่องจากไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/groupshape/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับรูปทรง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/groupshape/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/groupshape/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปทรง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/groupshape/hyperlink_click/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/groupshape/hyperlink_mouse_over/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการชี้เมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/groupshape/hyperlink_manager/) | คืนค่า hyperlink manager.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/groupshape/hidden/) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/groupshape/z_order_position/) | คืนค่าตำแหน่งของรูปทรงใน z-order.<br/>            Shapes[0] คืนค่ารูปทรงที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปทรงที่อยู่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/groupshape/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/groupshape/rotation/) | คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงกำหนดหมุนรอบแกน z<br/>            ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/groupshape/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง (หน่วยเป็น points).<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/groupshape/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง (หน่วยเป็น points).<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/groupshape/width/) | รับหรือกำหนดความกว้างของรูปทรง (หน่วยเป็น points).<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/groupshape/height/) | รับหรือกำหนดความสูงของรูปทรง (หน่วยเป็น points).<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/groupshape/black_white_mode/) | คุณสมบัติกำหนดว่ารูปทรงจะแสดงผลในโหมดสีขาวและดำอย่างไร..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/groupshape/unique_id/) | คืนค่าตัวระบุภายในที่ใช้สำหรับการเพิ่ม-อิน หรือโค้ดอื่น ๆ.<br/>            เนื่องจากค่าดังกล่าวอาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม จึงต้องไม่ถือเป็นคีย์ที่ไม่เปลี่ยนแปลง.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/groupshape/office_interop_shape_id/) | คืนค่าตัวระบุสไลด์-scoped ที่คงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรึงจากที่ใดก็ได้ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/groupshape/alternative_text/) | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/groupshape/alternative_text_title/) | คืนค่าหรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/groupshape/name/) | คืนค่าหรือกำหนดชื่อของรูปทรง.<br/>            ต้องไม่เป็น None. ใช้ค่า empty string หากต้องการ.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/groupshape/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/groupshape/shape_lock/) | คืนค่าการล็อคของรูปทรง.<br/>            อ่านอย่างเดียว [`IGroupShapeLock`](/slides/python-net/th/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/groupshape/is_grouped/) | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/groupshape/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หากรูปทรงอยู่ในกลุ่ม มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/groupshape/slide/) | คืนค่า slide พาเรนท์ของรูปทรง.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/groupshape/presentation/) | คืนค่า presentation พาเรนท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/th/aspose.slides/groupshape/group_shape_lock/) | คืนค่าการล็อคของรูปทรง.<br/>            อ่านอย่างเดียว [`IGroupShapeLock`](/slides/python-net/th/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/th/aspose.slides/groupshape/shapes/) | คืนค่าชุดของรูปทรงภายในกลุ่ม.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/groupshape/get_image/#) | คืนค่าตัวอย่างขนาดย่อของรูปทรง.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | คืนค่าตัวอย่างขนาดย่อของรูปทรง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/groupshape/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/groupshape/remove_placeholder/#) | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/groupshape/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติ placeholder ให้กับอันที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/groupshape/get_base_placeholder/#) | คืนค่า placeholder shape พื้นฐาน (shape จาก layout และ/หรือ master slide ที่รูปทรงปัจจุบันสืบทอดมา).<br/>            คืนค่า None หากรูปทรงปัจจุบันไม่สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/groupshape/get_visual_bounds/#) | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่แสดงผล. |


### ดูเพิ่มเติม
* class [`GroupShape`](/slides/python-net/th/aspose.slides/groupshape)
* class [`Shape`](/slides/python-net/th/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)