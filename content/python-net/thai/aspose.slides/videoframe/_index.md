---
title: VideoFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/videoframe/
---
## VideoFrame คลาส

แสดงคลิปวิดีโอบนสไลด์.

**การสืบทอด:**[`VideoFrame`](/slides/python-net/th/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท VideoFrame แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/videoframe/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/videoframe/placeholder/) | คืนค่า placeholder สำหรับ shape. คืนค่า None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/videoframe/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/videoframe/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติของกรอบ shape ดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/videoframe/frame/) | คืนค่า หรือกำหนดคุณสมบัติของกรอบ shape.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/videoframe/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/videoframe/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/videoframe/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติของเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/videoframe/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/videoframe/hyperlink_click/) | คืนค่า หรือกำหนด hyperlink ที่กำหนดไว้สำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/videoframe/hyperlink_mouse_over/) | คืนค่า หรือกำหนด hyperlink ที่กำหนดไว้สำหรับการวางเมาส์เหนือ.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/videoframe/hyperlink_manager/) | คืนค่า hyperlink manager.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/videoframe/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/videoframe/z_order_position/) | คืนค่าตำแหน่งของ shape ในลำดับ z.<br/>            Shapes[0] คืนค่า shape ที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/videoframe/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/videoframe/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่ shape ที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/videoframe/x/) | รับ หรือกำหนดค่า x-coordinate ของมุมซ้ายบนของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/videoframe/y/) | รับ หรือกำหนดค่า y-coordinate ของมุมซ้ายบนของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/videoframe/width/) | รับ หรือกำหนดค่าความกว้างของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/videoframe/height/) | รับ หรือกำหนดค่าสูงของ shape, วัดเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/videoframe/black_white_mode/) | คุณสมบัตินี้ระบุวิธีที่ shape จะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/videoframe/unique_id/) | คืนค่าตัวระบุภายในที่จำกัดขอบเขตการนำเสนอซึ่งตั้งใจใช้โดยแอดอินหรือโค้ดอื่น.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/videoframe/office_interop_shape_id/) | คืนค่าตัวระบุที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างมั่นใจจากทุกที่ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/videoframe/alternative_text/) | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/videoframe/alternative_text_title/) | คืนค่า หรือกำหนดหัวเรื่องของข้อความแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/videoframe/name/) | คืนค่า หรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างถ้าจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/videoframe/is_decorative/) | รับ หรือกำหนดตัวเลือก 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/videoframe/shape_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/videoframe/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/videoframe/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พาเร้นท์หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/videoframe/slide/) | คืนค่า slide พาเร้นท์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/videoframe/presentation/) | คืนค่าการนำเสนอพาเร้นท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/videoframe/shape_style/) | คืนค่าอ็อบเจ็กต์สไตล์ของ shape.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/videoframe/shape_type/) | คืนค่า หรือกำหนดประเภท AutoShape สำหรับ PictureFrame.<br/>            ชุดที่อนุญาตทั้งหมดคือ [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype), <br/>            ยกเว้นประเภทของเส้นต่าง ๆ:<br/><br/>    ShapeType.Line,<br/>    ShapeType.StraightConnector1,<br/>    ShapeType.BentConnector2,<br/>    ShapeType.BentConnector3,<br/>    ShapeType.BentConnector4,<br/>    ShapeType.BentConnector5,<br/>    ShapeType.CurvedConnector2,<br/>    ShapeType.CurvedConnector3,<br/>    ShapeType.CurvedConnector4,<br/>    ShapeType.CurvedConnector5.<br/><br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/videoframe/adjustments/) | คืนค่าคอลเลกชันของค่าการปรับของ shape.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/th/aspose.slides/videoframe/picture_frame_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/th/aspose.slides/videoframe/picture_format/) | คืนค่าอ็อบเจ็กต์ PictureFillFormat สำหรับ picture frame.<br/>            อ่านอย่างเดียว [`IPictureFillFormat`](/slides/python-net/th/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/th/aspose.slides/videoframe/relative_scale_height/) | คืนค่า หรือกำหนดอัตราส่วนความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 หมายถึง 100%.<br/>            อ่าน/เขียน **float**. |
| [`relative_scale_width`](/slides/python-net/th/aspose.slides/videoframe/relative_scale_width/) | คืนค่า หรือกำหนดอัตราส่วนความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 หมายถึง 100%.<br/>            อ่าน/เขียน **float**. |
| [`is_cameo`](/slides/python-net/th/aspose.slides/videoframe/is_cameo/) | กำหนดว่า PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`rewind_video`](/slides/python-net/th/aspose.slides/videoframe/rewind_video/) | กำหนดว่าวิดีโอจะถูกรีวินด์อัตโนมัติไปยังจุดเริ่มต้นเมื่อภาพยนตร์เล่นจบหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`play_loop_mode`](/slides/python-net/th/aspose.slides/videoframe/play_loop_mode/) | กำหนดว่าวิดีโอวนซ้ำหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`hide_at_showing`](/slides/python-net/th/aspose.slides/videoframe/hide_at_showing/) | กำหนดว่า VideoFrame ซ่อนอยู่หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`volume`](/slides/python-net/th/aspose.slides/videoframe/volume/) | คืนค่า หรือกำหนดระดับเสียง.<br/>            อ่าน/เขียน [`AudioVolumeMode`](/slides/python-net/th/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/th/aspose.slides/videoframe/play_mode/) | คืนค่า หรือกำหนดโหมดการเล่นวิดีโอ.<br/>            อ่าน/เขียน [`VideoPlayModePreset`](/slides/python-net/th/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/th/aspose.slides/videoframe/full_screen_mode/) | กำหนดว่าวิดีโอแสดงในโหมดเต็มหน้าจอหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`link_path_long`](/slides/python-net/th/aspose.slides/videoframe/link_path_long/) | คืนค่า หรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame.<br/>            อ่าน/เขียน **str**. |
| [`embedded_video`](/slides/python-net/th/aspose.slides/videoframe/embedded_video/) | คืนค่า หรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังอยู่.<br/>            อ่าน/เขียน [`IVideo`](/slides/python-net/th/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/th/aspose.slides/videoframe/trim_from_start/) | ตัดเริ่มต้น [ms] |
| [`trim_from_end`](/slides/python-net/th/aspose.slides/videoframe/trim_from_end/) | ตัดส่วนท้าย [ms] |
| [`caption_tracks`](/slides/python-net/th/aspose.slides/videoframe/caption_tracks/) | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ video frame.<br/>             คุณสมบัตินี้เป็นอ่านอย่างเดียวและคืนค่า [`ICaptionsCollection`](/slides/python-net/th/aspose.slides/icaptionscollection) ที่ประกอบด้วยแทร็กคำบรรยายทั้งหมด. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/videoframe/get_image/#) | คืนค่าภาพย่อของ shape.<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/videoframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/videoframe/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/videoframe/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder เป็นค่าที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/videoframe/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/videoframe/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/videoframe/get_geometry_paths/#) | คืนค่าคัดลอกของเส้นทางของ shape เรขาคณิต. พิกัดเป็นสัมพันธ์กับมุมซ้ายบนของ shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | อัปเดตรูปทรงของ shape จากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องเป็นสัมพันธ์กับมุมซ้ายบนของ shape.<br/>             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | อัปเดตรูปทรงของ shape จากอาเรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องเป็นสัมพันธ์กับมุมซ้ายบนของ shape.<br/>             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/videoframe/create_shape_elements/#) | สร้างและคืนค่าอาเรย์ขององค์ประกอบของ shape. |

### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`VideoFrame`](/slides/python-net/th/aspose.slides/videoframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)