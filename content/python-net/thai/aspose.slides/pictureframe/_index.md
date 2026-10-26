---
title: PictureFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/pictureframe/
---
## PictureFrame คลาส

แสดงกรอบที่มีรูปภาพอยู่ภายใน.

**การสืบทอด:**[`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท PictureFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/pictureframe/is_text_holder/) | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/pictureframe/placeholder/) | คืนค่าตัวแทนสำหรับรูปทรง. คืนค่า None หากรูปทรงไม่มีตัวแทน.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/pictureframe/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของรูปทรง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/pictureframe/raw_frame/) | คืนค่าหรือกำหนดคุณสมบัติกรอบรูปทรงดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/pictureframe/frame/) | คืนค่าหรือกำหนดคุณสมบัติกรอบรูปทรง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/pictureframe/line_format/) | คืนค่าอ็อบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/pictureframe/three_d_format/) | คืนค่าอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/pictureframe/effect_format/) | คืนค่าอ็อบเจกต์ EffectFormat ซึ่งมีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติของเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/pictureframe/fill_format/) | คืนค่าอ็อบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/pictureframe/hyperlink_click/) | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/pictureframe/hyperlink_mouse_over/) | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/pictureframe/hyperlink_manager/) | คืนค่าไฮเปอร์ลิงก์เมเนเจอร์.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/pictureframe/hidden/) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/pictureframe/z_order_position/) | คืนค่าตำแหน่งของรูปทรงในลำดับ z.<br/>            Shapes[0] คืนค่ารูปทรงที่อยู่ด้านหลังสุดของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปทรงที่อยู่ด้านหน้าสุดของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/pictureframe/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/pictureframe/rotation/) | คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z<br/>            ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/pictureframe/x/) | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปทรง, หน่วยเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/pictureframe/y/) | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปทรง, หน่วยเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/pictureframe/width/) | รับหรือกำหนดความกว้างของรูปทรง, หน่วยเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/pictureframe/height/) | รับหรือกำหนดความสูงของรูปทรง, หน่วยเป็นพอยท์.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/pictureframe/black_white_mode/) | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์ในโหมดแสดงสีขาว-ดำอย่างไร.<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/pictureframe/unique_id/) | คืนค่าตัวระบุภายในที่มีช่วงการใช้งานระดับการนำเสนอ เพื่อใช้โดยส่วนเสริมหรือโค้ดอื่น.<br/>            เนื่องจากค่านี้สามารถกำหนดค่าใหม่ได้โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/pictureframe/office_interop_shape_id/) | คืนค่าตัวระบุเฉพาะสไลด์ที่เป็นเอกลักษณ์ซึ่งคงที่ตลอดอายุของรูปทรงและ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างแม่นยำจากทุกตำแหน่งในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/pictureframe/alternative_text/) | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/pictureframe/alternative_text_title/) | คืนค่าหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/pictureframe/name/) | คืนค่าหรือกำหนดชื่อของรูปทรง.<br/>            ต้องไม่เป็น None. ใช้ค่าสตริงว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/pictureframe/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/pictureframe/shape_lock/) | คืนค่าการล็อคของรูปทรง.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/pictureframe/is_grouped/) | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/pictureframe/parent_group/) | คืนค่าอ็อบเจกต์ GroupShape พาเรนต์หากรูปทรงถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/pictureframe/slide/) | คืนสไลด์พาเรนต์ของรูปทรง.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/pictureframe/presentation/) | คืนการนำเสนอพาเรนต์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/pictureframe/shape_style/) | คืนอ็อบเจกต์สไตล์ของรูปทรง.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/pictureframe/shape_type/) | คืนค่าหรือกำหนดประเภท AutoShape สำหรับ PictureFrame.<br/>            มีรายการที่อนุญาตทั้งหมดในชุด [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype), <br/>            ยกเว้นเส้นทุกรูปแบบ:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/pictureframe/adjustments/) | คืนค่าคอลเลกชันของค่าการปรับของรูปทรง.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/th/aspose.slides/pictureframe/picture_frame_lock/) | คืนค่าการล็อคของรูปทรง.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/th/aspose.slides/pictureframe/picture_format/) | คืนค่าอ็อบเจกต์ PictureFillFormat สำหรับกรอบรูปภาพ.<br/>            อ่านอย่างเดียว [`IPictureFillFormat`](/slides/python-net/th/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/th/aspose.slides/pictureframe/relative_scale_height/) | คืนค่าหรือกำหนดสเกลของความสูง (เทียบกับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. ค่า 1.0 เท่ากับ 100%.<br/>            อ่าน/เขียน **float**. |
| [`relative_scale_width`](/slides/python-net/th/aspose.slides/pictureframe/relative_scale_width/) | คืนค่าหรือกำหนดสเกลของความกว้าง (เทียบกับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. ค่า 1.0 เท่ากับ 100%.<br/>            อ่าน/เขียน **float**. |
| [`is_cameo`](/slides/python-net/th/aspose.slides/pictureframe/is_cameo/) | กำหนดว่า PictureFrame เป็นอ็อบเจกต์ Cameo หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/pictureframe/get_image/#) | คืนค่าตัวอย่างย่อของรูปทรง.<br/>            ShapeThumbnailBounds.Shape ใช้ประเภทขอบเขตตัวอย่างย่อของรูปทรงเป็นค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าตัวอย่างย่อของรูปทรง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของรูปทรงเป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของรูปทรงเป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/pictureframe/remove_placeholder/#) | กำหนดว่ารูปทรงนี้ไม่ใช่ตัวแทน. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | เพิ่มตัวแทนใหม่หากไม่มีและกำหนดคุณสมบัติตัวแทนให้กับที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/pictureframe/get_base_placeholder/#) | คืนค่ารูปทรงตัวแทนพื้นฐาน (รูปทรงจากเลเอาต์และ/หรือสไลด์หลักที่รูปทรงปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หากรูปทรงปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/pictureframe/get_visual_bounds/#) | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/pictureframe/get_geometry_paths/#) | คืนค่าคัดลอกของเส้นทางของรูปทรงเรขาคณิต. พิกัดอ้างอิงจากมุมซ้ายบนของรูปทรง. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจกต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้าย<br/>             บนของรูปทรง.<br/>             เปลี่ยนประเภทของรูปทรง ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | อัปเดตเรขาคณิตของรูปทรงจากอาเรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้าย<br/>             บนของรูปทรง.<br/>             เปลี่ยนประเภทของรูปทรง ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/pictureframe/create_shape_elements/#) | สร้างและคืนค่าอาเรย์ขององค์ประกอบของรูปทรง. |

### ดูเพิ่มเติม
* class [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* class [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* class [`Shape`](/slides/python-net/th/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)