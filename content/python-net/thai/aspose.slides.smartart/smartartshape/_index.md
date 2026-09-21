---
title: SmartArtShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.smartart/smartartshape/
---
## SmartArtShape คลาส

Represents SmartArt shape

**การสืบทอด:**[`SmartArtShape`](/slides/python-net/th/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

The SmartArtShape type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides.smartart/smartartshape/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides.smartart/smartartshape/placeholder/) | คืนค่าตัวแทนตำแหน่งของ shape. คืนค่า None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides.smartart/smartartshape/custom_data/) | คืนค่าข้อมูลกำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides.smartart/smartartshape/raw_frame/) | คืนค่า或กำหนดคุณสมบัติกรอบของ shape ดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides.smartart/smartartshape/frame/) | คืนค่า或กำหนดคุณสมบัติกรอบของ shape.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides.smartart/smartartshape/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่บรรจุคุณสมบัติดีไซน์เส้นสำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides.smartart/smartartshape/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเผลิดผล 3d สำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides.smartart/smartartshape/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides.smartart/smartartshape/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีสำหรับ shape.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides.smartart/smartartshape/hyperlink_click/) | คืนค่า或กำหนด hyperlink ที่กำหนดสำหรับคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | คืนค่า或กำหนด hyperlink ที่กำหนดสำหรับเมาส์อยู่เหนือ.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides.smartart/smartartshape/hyperlink_manager/) | คืนค่า hyperlink manager.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides.smartart/smartartshape/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides.smartart/smartartshape/z_order_position/) | คืนตำแหน่งของ shape ใน z-order.<br/>            Shapes[0] คืนค่า shape ที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides.smartart/smartartshape/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides.smartart/smartartshape/rotation/) | คืนค่า或กำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z<br/>            ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides.smartart/smartartshape/x/) | รับหรือกำหนดค่า x-coordinate ของมุมซ้ายบนของ shape, หน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides.smartart/smartartshape/y/) | รับหรือกำหนดค่า y-coordinate ของมุมซ้ายบนของ shape, หน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides.smartart/smartartshape/width/) | รับหรือกำหนดความกว้างของ shape, หน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides.smartart/smartartshape/height/) | รับหรือกำหนดความสูงของ shape, หน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides.smartart/smartartshape/black_white_mode/) | คุณสมบัติเชื่อกำหนดว่า shape จะเรนเดอร์อย่างไรในโหมดแสดงผลขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides.smartart/smartartshape/unique_id/) | คืนค่าอัตลักษณ์ภายในที่กำหนดขอบเขตการนำเสนอซึ่งตั้งใจให้ใช้โดย add-ins หรือโค้ดอื่น.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | คืนค่าอัตลักษณ์ที่มีขอบเขตสไลด์และเป็นเอกลักษณ์ซึ่งคงที่ตลอดอายุของ shape และ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape อย่างเชื่อถือได้จากทุกตำแหน่งในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides.smartart/smartartshape/alternative_text/) | คืนค่า或กำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides.smartart/smartartshape/alternative_text_title/) | คืนค่า或กำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides.smartart/smartartshape/name/) | คืนค่า或กำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่า string ว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides.smartart/smartartshape/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides.smartart/smartartshape/shape_lock/) | คืนค่าการล็อกของ shape.<br/>            อ่านอย่างเดียว [`IBaseShapeLock`](/slides/python-net/th/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides.smartart/smartartshape/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides.smartart/smartartshape/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides.smartart/smartartshape/slide/) | คืนสไลด์พาเรนท์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides.smartart/smartartshape/presentation/) | คืนการนำเสนอพาเรนท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides.smartart/smartartshape/shape_style/) | คืนอ็อบเจ็กต์สไตล์ของ shape.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides.smartart/smartartshape/shape_type/) | คืนค่า或กำหนดประเภท preset ของ geometry.<br/>            หมายเหตุ: เมื่อค่ามีการเปลี่ยนแปลง ค่า adjustment ทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น.<br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides.smartart/smartartshape/adjustments/) | คืนคอลเลกชันของค่า adjustment ของ shape.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/th/aspose.slides.smartart/smartartshape/text_frame/) | คืนข้อความของ SmartArt shape.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/get_image/#) | คืนค่า thumbnail ของ shape.<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape shape thumbnail bounds เป็นค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | คืนค่า thumbnail ของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติ placeholder ให้กับที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดจาก).<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | คืนสำเนาของ path ของ geometry shape. พิกัดอ้างอิงจากมุมซ้ายบนของ shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | อัปเดต geometry ของ shape จากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอ้างอิงจากด้านซ้าย<br/>             ด้านบนของ shape.<br/>             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | อัปเดต geometry ของ shape จากอาร์เรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอ้างอิงจากด้านซ้าย<br/>             ด้านบนของ shape.<br/>             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides.smartart/smartartshape/create_shape_elements/#) | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของ shape. |

### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`SmartArtShape`](/slides/python-net/th/aspose.slides.smartart/smartartshape)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)