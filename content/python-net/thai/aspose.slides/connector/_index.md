---
title: Connector class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/connector/
---
## Connector คลาส

อธิบายคอนเน็กเตอร์.

**การสืบทอด:**[`Connector`](/slides/python-net/th/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท Connector เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/connector/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/connector/placeholder/) | ส่งคืน placeholder ของ shape. ส่งคืน None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/connector/custom_data/) | ส่งคืนข้อมูลกำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/connector/raw_frame/) | ส่งคืนหรือกำหนดคุณสมบัติของ raw shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/connector/frame/) | ส่งคืนหรือกำหนดคุณสมบัติของ shape frame.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/connector/line_format/) | ส่งคืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: อาจส่งคืน None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/connector/three_d_format/) | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับ shape.<br/>            หมายเหตุ: อาจส่งคืน None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/connector/effect_format/) | ส่งคืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: อาจส่งคืน Nil สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/connector/fill_format/) | ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape.<br/>            หมายเหตุ: อาจส่งคืน Nil สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติการเติม.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/connector/hyperlink_click/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/connector/hyperlink_mouse_over/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์เหนือ.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/connector/hyperlink_manager/) | ส่งคืนผู้จัดการ hyperlink.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/connector/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/connector/z_order_position/) | ส่งคืนตำแหน่งของ shape ใน z-order.<br/>            Shapes[0] ส่งคืน shape ที่สุดท้ายของ z-order,<br/>            และ Shapes[Shapes.Count - 1] ส่งคืน shape ที่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/connector/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/connector/rotation/) | ส่งคืนหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z<br/>            ค่าเป็นบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/connector/x/) | รับหรือกำหนดค่า x-coordinate ของมุมบนซ้ายของ shape โดยหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/connector/y/) | รับหรือกำหนดค่า y-coordinate ของมุมบนซ้ายของ shape โดยหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/connector/width/) | รับหรือกำหนดความกว้างของ shape โดยหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/connector/height/) | รับหรือกำหนดความสูงของ shape โดยหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/connector/black_white_mode/) | คุณสมบัตินี้ระบุว่ารูปแบบ shape จะถูกแสดงอย่างไรในโหมดสีขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/connector/unique_id/) | ส่งคืนตัวระบุภายในที่มีขอบเขตระดับการนำเสนอซึ่งตั้งใจให้ใช้โดย add-in หรือโค้ดอื่นๆ.<br/>            เนื่องจากค่า này สามารถถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่คงที่และไม่ซ้ำกัน.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/connector/office_interop_shape_id/) | ส่งคืนตัวระบุเฉพาะสไลด์ที่คงที่ตลอดอายุของ shape และ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape อย่างเชื่อถือได้จากทุกตำแหน่งในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/connector/alternative_text/) | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/connector/alternative_text_title/) | ส่งคืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/connector/name/) | ส่งคืนหรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าเป็นสตริงว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/connector/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/connector/shape_lock/) | ส่งคืน locks ของ shape.<br/>            อ่านอย่างเดียว [`IConnectorLock`](/slides/python-net/th/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/connector/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/connector/parent_group/) | ส่งคืนอ็อบเจ็กต์ GroupShape พาเรนท์ถ้า shape ถูกจัดกลุ่ม. มิฉะนั้นส่งคืน None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/connector/slide/) | ส่งคืนสไลด์พาเรนท์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/connector/presentation/) | ส่งคืนการนำเสนอพาเรนท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/connector/shape_style/) | ส่งคืนอ็อบเจ็กต์ style ของ shape.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/connector/shape_type/) | ส่งคืนหรือกำหนดประเภท AutoShape.<br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/connector/adjustments/) | ส่งคืนคอลเลกชันของค่าการปรับของ shape.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/th/aspose.slides/connector/connector_lock/) | ส่งคืน locks ของ connector.<br/>            อ่านอย่างเดียว [`IConnectorLock`](/slides/python-net/th/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/th/aspose.slides/connector/start_shape_connected_to/) | ส่งคืนหรือกำหนด shape ที่เชื่อมต่อจุดเริ่มต้นของ connector.<br/>            อ่าน/เขียน [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/th/aspose.slides/connector/end_shape_connected_to/) | ส่งคืนหรือกำหนด shape ที่เชื่อมต่อจุดสิ้นของ connector.<br/>            อ่าน/เขียน [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/th/aspose.slides/connector/start_shape_connection_site_index/) | ส่งคืนหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น.<br/>            อ่าน/เขียน **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/th/aspose.slides/connector/end_shape_connection_site_index/) | ส่งคืนหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape สิ้นสุด.<br/>            อ่าน/เขียน **int**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/connector/get_image/#) | ส่งคืน thumbnail ของ shape.<br/>            รูปแบบ ShapeThumbnailBounds.Shape shape thumbnail bounds ถูกใช้เป็นค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | ส่งคืน thumbnail ของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/connector/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/connector/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/connector/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้เป็นที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/connector/get_base_placeholder/#) | ส่งคืน shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมา).<br/>            ส่งคืน None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/connector/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/connector/get_geometry_paths/#) | ส่งคืนสำเนา path ของ shape รูปร่างเรขาคณิต. พิกัดอิงตามมุมซ้ายบนของ shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/connector/set_geometry_path/#igeometrypath) | อัปเดตเรขาคณิตของ shape จากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอิงตามมุมซ้าย<br/>             บนของ shape.<br/>             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | อัปเดตเรขาคณิตของ shape จากอาร์เรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอิงตามมุมซ้าย<br/>             บนของ shape.<br/>             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/connector/create_shape_elements/#) | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของ shape. |
| [`reroute(self)`](/slides/python-net/th/aspose.slides/connector/reroute/#) | เปลี่ยนเส้นทางของ connector เพื่อให้เส้นทางสั้นที่สุดระหว่าง shape ที่เชื่อมต่อ. |

### ดูเพิ่มเติม
* class [`Connector`](/slides/python-net/th/aspose.slides/connector)
* class [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/th/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)