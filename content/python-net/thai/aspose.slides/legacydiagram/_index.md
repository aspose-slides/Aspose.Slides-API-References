---
title: LegacyDiagram class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/legacydiagram/
---
## คลาส LegacyDiagram

แทนวัตถุไดอะแกรมรุ่นเก่า.

**การสืบทอด:**[`LegacyDiagram`](/slides/python-net/th/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท LegacyDiagram มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/legacydiagram/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/legacydiagram/placeholder/) | ส่งคืน placeholder ของ shape. ส่งคืน None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/legacydiagram/custom_data/) | ส่งคืน custom data ของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/legacydiagram/raw_frame/) | ส่งคืนหรือกำหนดคุณสมบัติของ raw shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/legacydiagram/frame/) | ส่งคืนหรือกำหนดคุณสมบัติของ shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/legacydiagram/line_format/) | ส่งคืนออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/legacydiagram/three_d_format/) | ส่งคืนออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/legacydiagram/effect_format/) | ส่งคืนออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติของเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/legacydiagram/fill_format/) | ส่งคืนออบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติการเติม.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/legacydiagram/hyperlink_click/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/legacydiagram/hyperlink_mouse_over/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการชี้เมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/legacydiagram/hyperlink_manager/) | ส่งคืนผู้จัดการ hyperlink.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/legacydiagram/hidden/) | กำหนดว่า shape ถูกซ่อนไว้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/legacydiagram/z_order_position/) | ส่งคืนตำแหน่งของ shape ใน z-order.<br/>            Shapes[0] ส่งคืน shape ที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] ส่งคืน shape ที่อยู่ด้านหน้า ของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/legacydiagram/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/legacydiagram/rotation/) | ส่งคืนหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบ<br/>            แกน z. ค่าเป็นบวกบ่งชี้การหมุนตามเข็มนาฬิกา; ค่าเป็นลบบ่งชี้การหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/legacydiagram/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของ shape, วัดเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/legacydiagram/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของ shape, วัดเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/legacydiagram/width/) | รับหรือกำหนดความกว้างของ shape, วัดเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/legacydiagram/height/) | รับหรือกำหนดความสูงของ shape, วัดเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/legacydiagram/black_white_mode/) | คุณสมบัตินี้ระบุว่า shape จะถูกแสดงอย่างไรในโหมดสีขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/legacydiagram/unique_id/) | ส่งคืนตัวระบุภายในที่มีช่วงการใช้งานระดับการนำเสนอซึ่งตั้งใจให้ใช้โดย add-ins หรือโค้ดอื่น.<br/>            เนื่องจากค่าดังกล่าวสามารถถูกกำหนดค่าใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์อย่างถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/legacydiagram/office_interop_shape_id/) | ส่งคืนตัวระบุเฉพาะสไลด์ที่เป็นเอกลักษณ์และคงที่ตลอดอายุของ shape และ<br/>            ให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากทุกที่ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/legacydiagram/alternative_text/) | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/legacydiagram/alternative_text_title/) | ส่งคืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/legacydiagram/name/) | ส่งคืนหรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/legacydiagram/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/legacydiagram/shape_lock/) | ส่งคืนล็อกของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/legacydiagram/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/legacydiagram/parent_group/) | ส่งคืนออบเจกต์ GroupShape พ่อแม่หาก shape ถูกจัดกลุ่ม. มิฉะนั้นส่งคืน None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/legacydiagram/slide/) | ส่งคืนสไลด์พาเรนท์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/legacydiagram/presentation/) | ส่งคืนการนำเสนอพาเรนท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/legacydiagram/graphical_object_lock/) | ส่งคืนล็อกของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/legacydiagram/get_image/#) | ส่งคืน thumbnail ของ shape.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | ส่งคืน thumbnail ของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/legacydiagram/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/legacydiagram/get_base_placeholder/#) | ส่งคืน shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            ส่งคืน None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/legacydiagram/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว. |
| [`convert_to_smart_art(self)`](/slides/python-net/th/aspose.slides/legacydiagram/convert_to_smart_art/#) | แปลง legacy digram เป็นออบเจกต์ SmartArt ที่แก้ไขได้.<br/>            SmartArt ออบเจกต์ที่สร้างขึ้นจะถูกเพิ่มไปยังกลุ่ม shape พาเรนท์ในตำแหน่งเดียวกัน. |
| [`convert_to_group_shape(self)`](/slides/python-net/th/aspose.slides/legacydiagram/convert_to_group_shape/#) | แปลง legacy digram เป็นกลุ่ม shape ที่แก้ไขได้.<br/>            GroupShape ออบเจกต์ที่สร้างขึ้นจะถูกเพิ่มไปยังกลุ่ม shape พาเรนท์ในตำแหน่งเดียวกัน. |

### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`LegacyDiagram`](/slides/python-net/th/aspose.slides/legacydiagram)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)