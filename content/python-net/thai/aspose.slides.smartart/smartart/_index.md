---
title: SmartArt class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.smartart/smartart/
---
## คลาส SmartArt

แทนแผนภาพ SmartArt

**Inheritance:**[`SmartArt`](/slides/python-net/th/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท SmartArt แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides.smartart/smartart/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides.smartart/smartart/placeholder/) | คืนค่า placeholder ของ shape. คืนค่า None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides.smartart/smartart/custom_data/) | คืนค่าข้อมูลกำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides.smartart/smartart/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติของกรอบ shape ดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides.smartart/smartart/frame/) | คืนค่า หรือกำหนดคุณสมบัติของกรอบ shape.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides.smartart/smartart/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ซึ่งมีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides.smartart/smartart/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ซึ่งมีคุณสมบัติผลลัพธ์ 3d สำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides.smartart/smartart/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ซึ่งมีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides.smartart/smartart/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ซึ่งมีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides.smartart/smartart/hyperlink_click/) | คืนค่า หรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | คืนค่า หรือกำหนด hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์ผ่าน.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides.smartart/smartart/hyperlink_manager/) | คืนค่า hyperlink manager.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides.smartart/smartart/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides.smartart/smartart/z_order_position/) | คืนค่าตำแหน่งของ shape ใน z-order.<br/>            Shapes[0] คืนค่า shape ที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides.smartart/smartart/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides.smartart/smartart/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบ<br/>            แกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides.smartart/smartart/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของ shape, หน่วยเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides.smartart/smartart/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของ shape, หน่วยเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides.smartart/smartart/width/) | รับหรือกำหนดความกว้างของ shape, หน่วยเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides.smartart/smartart/height/) | รับหรือกำหนดความสูงของ shape, หน่วยเป็น point.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides.smartart/smartart/black_white_mode/) | คุณสมบัติระบุว่ารูปร่างจะถูกแสดงผลอย่างไรในโหมดแสดงสีขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides.smartart/smartart/unique_id/) | คืนค่าออบเจ็กต์ตัวระบุภายในที่มีขอบเขตการนำเสนอ ซึ่งตั้งใจให้ใช้โดย add-in หรือโค้ดอื่น.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่ไม่เปลี่ยนแปลง.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides.smartart/smartart/office_interop_shape_id/) | คืนค่าตัวระบุเฉพาะสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop อ้างอิง shape ได้อย่างเชื่อถือจากทุกส่วนของเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides.smartart/smartart/alternative_text/) | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides.smartart/smartart/alternative_text_title/) | คืนค่า หรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides.smartart/smartart/name/) | คืนค่า หรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides.smartart/smartart/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides.smartart/smartart/shape_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides.smartart/smartart/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides.smartart/smartart/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พารents หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides.smartart/smartart/slide/) | คืนค่าสไลด์แม่ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides.smartart/smartart/presentation/) | คืนค่าการนำเสนอแม่ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides.smartart/smartart/graphical_object_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/th/aspose.slides.smartart/smartart/all_nodes/) | คืนค่าคอลเลกชันของโหนดทั้งหมดในอ็อบเจ็กต์ SmartArt.<br/>            อ่านอย่างเดียว [`ISmartArtNodeCollection`](/slides/python-net/th/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/th/aspose.slides.smartart/smartart/nodes/) | คืนค่าคอลเลกชันของโหนดรากในอ็อบเจ็กต์ SmartArt.<br/>            อ่านอย่างเดียว [`ISmartArtNodeCollection`](/slides/python-net/th/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/th/aspose.slides.smartart/smartart/layout/) | คืนค่า หรือกำหนด layout ของอ็อบเจ็กต์ SmartArt.<br/>            อ่าน/เขียน [`SmartArtLayoutType`](/slides/python-net/th/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/th/aspose.slides.smartart/smartart/quick_style/) | คืนค่า หรือกำหนดสไตล์ด่วนของอ็อบเจ็กต์ SmartArt.<br/>            อ่าน/เขียน [`SmartArtQuickStyleType`](/slides/python-net/th/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/th/aspose.slides.smartart/smartart/color_style/) | คืนค่า หรือกำหนดสไตล์สีของอ็อบเจ็กต์ SmartArt.<br/>            อ่าน/เขียน [`SmartArtColorType`](/slides/python-net/th/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/th/aspose.slides.smartart/smartart/is_reversed/) | คืนค่า หรือกำหนดสถานะของไดอะแกรม SmartArt เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL, หากไดอะแกรมสนับสนุนการย้อนกลับ.<br/>            อ่าน/เขียน **bool**. |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides.smartart/smartart/get_image/#) | คืนค่าภาพย่อของ shape.<br/>            ชนิด ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของ shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides.smartart/smartart/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติ placeholder ให้กับออบเจ็กต์ที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides.smartart/smartart/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides.smartart/smartart/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |

### ดูเพิ่ม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`SmartArt`](/slides/python-net/th/aspose.slides.smartart/smartart)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)