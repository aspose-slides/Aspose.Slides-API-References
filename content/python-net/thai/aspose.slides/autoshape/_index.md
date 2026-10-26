---
title: AutoShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/autoshape/
---
## คลาส AutoShape

เป็นตัวแทนของ AutoShape.

**การสืบทอด:**[`AutoShape`](/slides/python-net/th/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท AutoShape เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/autoshape/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/autoshape/placeholder/) | ส่งคืน placeholder สำหรับ shape. ส่งคืน None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/autoshape/custom_data/) | ส่งคืนข้อมูลที่กำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/autoshape/raw_frame/) | ส่งคืนหรือกำหนดคุณสมบัติของ raw shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/autoshape/frame/) | ส่งคืนหรือกำหนดคุณสมบัติของ shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/autoshape/line_format/) | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/autoshape/three_d_format/) | ส่งคืนวัตถุ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/autoshape/effect_format/) | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/autoshape/fill_format/) | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติการเติม.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/autoshape/hyperlink_click/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/autoshape/hyperlink_mouse_over/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการชี้เมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/autoshape/hyperlink_manager/) | ส่งคืนผู้จัดการ hyperlink.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/autoshape/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/autoshape/z_order_position/) | ส่งคืนตำแหน่งของ shape ในลำดับ z-order.<br/>            Shapes[0] ส่งคืน shape ที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] ส่งคืน shape ที่อยู่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/autoshape/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/autoshape/rotation/) | ส่งคืนหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/autoshape/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/autoshape/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/autoshape/width/) | รับหรือกำหนดความกว้างของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/autoshape/height/) | รับหรือกำหนดความสูงของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/autoshape/black_white_mode/) | คุณสมบัติเก็บวิธีการแสดงผลของ shape ในโหมดแสดงผลขาวดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/autoshape/unique_id/) | ส่งคืนตัวระบุภายในระดับการนำเสนอที่ตั้งใจให้ใช้โดย add-ins หรือโค้ดอื่น.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำกันแบบถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/autoshape/office_interop_shape_id/) | ส่งคืนตัวระบุเฉพาะสไลด์ที่เป็นเอกลักษณ์ซึ่งคงที่ตลอดอายุของ shape และ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างมั่นใจจากทุกที่ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/autoshape/alternative_text/) | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/autoshape/alternative_text_title/) | ส่งคืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/autoshape/name/) | ส่งคืนหรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างเป็นสตริงหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/autoshape/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/autoshape/shape_lock/) | ส่งคืนการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IAutoShapeLock`](/slides/python-net/th/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/autoshape/is_grouped/) | กำหนดว่า shape อยู่ในกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/autoshape/parent_group/) | ส่งคืนอ็อบเจ็กต์ GroupShape พาเรนต์หาก shape อยู่ในกลุ่ม. มิฉะนั้นส่งคืน None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/autoshape/slide/) | ส่งคืนสไลด์พาเรนต์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/autoshape/presentation/) | ส่งคืนการนำเสนอพาเรนต์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/autoshape/shape_style/) | ส่งคืนอ็อบเจ็กต์สไตล์ของ shape.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/autoshape/shape_type/) | ส่งคืนหรือกำหนดประเภท geometry preset.<br/>            หมายเหตุ: เมื่อเปลี่ยนค่า จะรีเซ็ตค่าการปรับทั้งหมดไปเป็นค่าเริ่มต้น.<br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/autoshape/adjustments/) | ส่งคืนคอลเลกชันของค่าการปรับของ shape.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/th/aspose.slides/autoshape/auto_shape_lock/) | ส่งคืนการล็อคของ autoshape.<br/>            อ่านอย่างเดียว [`IAutoShapeLock`](/slides/python-net/th/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/th/aspose.slides/autoshape/text_frame/) | ส่งคืนอ็อบเจ็กต์ TextFrame สำหรับ AutoShape.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/th/aspose.slides/autoshape/use_background_fill/) | กำหนดว่า autoshape นี้ควรเติมด้วยพื้นหลังของสไลด์แทนการกำหนดโดยสไตล์หรือรูปแบบการเติมหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`is_text_box`](/slides/python-net/th/aspose.slides/autoshape/is_text_box/) | ระบุว่า shape เป็น text box หรือไม่. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/autoshape/get_image/#) | ส่งคืน thumbnail ของ shape.<br/>            ใช้ ShapeThumbnailBounds.Shape เป็นประเภทขอบเขต thumbnail ของ shape โดยค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | ส่งคืน thumbnail ของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/autoshape/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/autoshape/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/autoshape/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/autoshape/get_base_placeholder/#) | ส่งคืน shape placeholder พื้นฐาน (shape จากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            ส่งคืน None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/autoshape/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่แสดงผล. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/autoshape/get_geometry_paths/#) | ส่งคืนสำเนาของเส้นทางของ geometry shape. พิกัดเป็นสัมพัทธ์กับมุมซ้ายบนของ shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | อัปเดต geometry ของ shape จากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องเป็นสัมพัทธ์กับมุมซ้าย<br/>            บนของ shape.<br/>            เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | อัปเดต geometry ของ shape จากอาร์เรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องเป็นสัมพัทธ์กับมุมซ้าย<br/>            บนของ shape.<br/>            เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/autoshape/create_shape_elements/#) | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของ shape. |
| [`add_text_frame(self, text)`](/slides/python-net/th/aspose.slides/autoshape/add_text_frame/#str) | เพิ่ม TextFrame ใหม่ให้กับ shape.<br/>            หาก shape มี TextFrame อยู่แล้วจะเปลี่ยนข้อความของมันเท่านั้น. |

### ดูเพิ่มเติม
* คลาส [`AutoShape`](/slides/python-net/th/aspose.slides/autoshape)
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)