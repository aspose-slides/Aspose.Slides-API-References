---
title: IShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ishape/
---
## IShape คลาส

เป็นการแทนรูปทรงบนสไลด์.

ประเภท IShape เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/ishape/is_text_holder/) | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/ishape/placeholder/) | ส่งคืนตัว placeholder สำหรับรูปทรง.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/ishape/custom_data/) | ส่งคืนข้อมูลกำหนดเองของรูปทรง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/ishape/raw_frame/) | ส่งคืนหรือกำหนดคุณสมบัติของเฟรมรูปทรงดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/ishape/frame/) | ส่งคืนหรือกำหนดคุณสมบัติของเฟรมรูปทรง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/ishape/line_format/) | ส่งคืนออบเจกต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปเส้นสำหรับรูปทรง.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/ishape/three_d_format/) | ส่งคืนออบเจกต์ ThreeDFormat ที่บรรจุคุณสมบัติการจัดรูปเส้นสำหรับรูปทรง.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/ishape/effect_format/) | ส่งคืนออบเจกต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/ishape/fill_format/) | ส่งคืนออบเจกต์ FillFormat ที่บรรจุคุณสมบัติการจัดรูปการเติมสีสำหรับรูปทรง.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/th/aspose.slides/ishape/hidden/) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ได้.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/ishape/z_order_position/) | ส่งคืนตำแหน่งของรูปทรงในลำดับ z.<br/>            Shapes[0] ส่งคืนรูปทรงที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] ส่งคืนรูปทรงที่อยู่ด้านหน้าของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/ishape/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปทรง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/ishape/rotation/) | ส่งคืนหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุหมุนรอบ<br/>            แกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/ishape/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง, วัดเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/ishape/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง, วัดเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/ishape/width/) | รับหรือกำหนดความกว้างของรูปทรง, วัดเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/ishape/height/) | รับหรือกำหนดความสูงของรูปทรง, วัดเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`alternative_text`](/slides/python-net/th/aspose.slides/ishape/alternative_text/) | ส่งคืนหรือกำหนดข้อความอธิบายภาพที่เกี่ยวข้องกับรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/ishape/alternative_text_title/) | ส่งคืนหรือกำหนดหัวข้อของข้อความอธิบายภาพที่เกี่ยวข้องกับรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/ishape/name/) | ส่งคืนหรือกำหนดชื่อของรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/ishape/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/ishape/shape_lock/) | ส่งคืนการล็อกของรูปทรง.<br/>            อ่านอย่างเดียว [`IBaseShapeLock`](/slides/python-net/th/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/th/aspose.slides/ishape/unique_id/) | ส่งคืนตัวระบุภายในที่อยู่ในขอบเขตของการนำเสนอซึ่งตั้งใจให้ใช้โดยแอด-อินหรือโค้ดอื่น.<br/>            เนื่องจากค่าดังกล่าวอาจถูกเปลี่ยนโดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`IShape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/ishape/office_interop_shape_id/) | ส่งคืนตัวระบุที่ไม่ซ้ำกันในขอบเขตของสไลด์ที่คงที่ตลอดอายุของรูปทรงและ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างมั่นใจจากทุกที่ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`IShape.unique_id`](/slides/python-net/th/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/ishape/is_grouped/) | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/ishape/black_white_mode/) | คุณสมบัติกำหนดว่ารูปทรงจะแสดงผลอย่างไรในโหมดสีดำและขาว..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/th/aspose.slides/ishape/parent_group/) | ส่งคืนออบเจกต์ GroupShape พ่อแม่หากรูปทรงถูกจัดกลุ่ม. มิฉะนั้นส่งคืน None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/ishape/hyperlink_manager/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/ishape/get_image/#) | ส่งคืนภาพย่อของรูปทรง.<br/>            ใช้ ShapeThumbnailBounds.Shape เป็นประเภทขอบเขตภาพย่อของรูปทรงโดยค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | ส่งคืนภาพย่อของรูปทรง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/ishape/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหของ Shape เป็นไฟล์ SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/ishape/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/ishape/remove_placeholder/#) | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/ishape/get_base_placeholder/#) | ส่งคืนรูปทรง placeholder พื้นฐาน (รูปทรงจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก).<br/>            ส่งคืน None หากรูปทรงปัจจุบันไม่ได้สืบทอด. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)