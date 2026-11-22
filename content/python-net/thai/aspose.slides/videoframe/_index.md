---
title: VideoFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/videoframe/
---
## VideoFrame คลาส

แสดงคลิปวิดีโอบนสไลด์.

**Inheritance:**[`VideoFrame`](/slides/python-net/th/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท VideoFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/videoframe/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/videoframe/placeholder/) | คืนค่าตัวกำหนดตำแหน่งสำหรับ shape. คืนค่า None หาก shape ไม่มีตัวกำหนดตำแหน่ง.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/videoframe/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/videoframe/raw_frame/) | คืนค่าหรือกำหนดคุณสมบัติของเฟรม shape ดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/videoframe/frame/) | คืนค่าหรือกำหนดคุณสมบัติของเฟรม shape.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/videoframe/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/videoframe/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟ็กต์ 3 มิติสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/videoframe/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่บรรจุเอฟเฟ็กต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเอฟเฟ็กต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/videoframe/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/videoframe/hyperlink_click/) | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/videoframe/hyperlink_mouse_over/) | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/videoframe/hyperlink_manager/) | คืนค่าตัวจัดการไฮเปอร์ลิงก์.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/videoframe/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/videoframe/z_order_position/) | คืนค่าตำแหน่งของ shape ในลำดับ z.<br/>            Shapes[0] คืนค่า shape ที่อยู่ด้านหลังสุดของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าสุดของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/videoframe/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/videoframe/rotation/) | คืนค่าหรือกำหนดจำนวนองศาที่ shape ถูกหมุนรอบแกน z<br/>            ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/videoframe/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/videoframe/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/videoframe/width/) | รับหรือกำหนดความกว้างของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/videoframe/height/) | รับหรือกำหนดความสูงของ shape, หน่วยเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/videoframe/black_white_mode/) | คุณสมบัติกำหนดว่า shape จะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/videoframe/unique_id/) | คืนค่าอิลิเด็นติเพรสเซนต์ภายในของการนำเสนอที่ออกแบบมาสำหรับใช้โดยแอดอินหรือโค้ดอื่น.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงต้องไม่ถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/videoframe/office_interop_shape_id/) | คืนค่าอิลิเด็นติเฉพาะของสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากทุกส่วนของเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/videoframe/alternative_text/) | คืนค่าหรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/videoframe/alternative_text_title/) | คืนค่าหรือกำหนดหัวเรื่องของข้อความแทนที่ที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/videoframe/name/) | คืนค่าหรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่า string ว่างหากจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/videoframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/videoframe/shape_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/videoframe/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/videoframe/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์ถ้า shape ถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/videoframe/slide/) | คืนค่า slide พาเรนท์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/videoframe/presentation/) | คืนค่าการนำเสนอพาเรนท์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/videoframe/shape_style/) | คืนค่าอ็อบเจ็กต์สไตล์ของ shape.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/videoframe/shape_type/) | คืนค่าหรือกำหนดประเภท AutoShape สำหรับ PictureFrame.<br/>            มีรายการที่อนุญาตทั้งหมดของชุด [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype), <br/>            ยกเว้นทุกประเภทของเส้น:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/videoframe/adjustments/) | คืนค่าชุดของค่าการปรับรูปของ shape.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/th/aspose.slides/videoframe/picture_frame_lock/) | คืนค่าการล็อคของ shape.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/th/aspose.slides/videoframe/picture_format/) | คืนค่าอ็อบเจ็กต์ PictureFillFormat สำหรับ picture frame.<br/>            อ่านอย่างเดียว [`IPictureFillFormat`](/slides/python-net/th/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/th/aspose.slides/videoframe/relative_scale_height/) | คืนค่าหรือกำหนดสเกลของความสูง (สัมพันธ์กับขนาดรูปต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%.<br/>            อ่าน/เขียน **float**. |
| [`relative_scale_width`](/slides/python-net/th/aspose.slides/videoframe/relative_scale_width/) | คืนค่าหรือกำหนดสเกลของความกว้าง (สัมพันธ์กับขนาดรูปต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%.<br/>            อ่าน/เขียน **float**. |
| [`is_cameo`](/slides/python-net/th/aspose.slides/videoframe/is_cameo/) | กำหนดว่า PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`rewind_video`](/slides/python-net/th/aspose.slides/videoframe/rewind_video/) | กำหนดว่า video จะถูกรีวินด์อัตโนมัติไปยังจุดเริ่มต้น<br/>            ทันทีที่หนังจบการเล่น.<br/>            อ่าน/เขียน **bool**. |
| [`play_loop_mode`](/slides/python-net/th/aspose.slides/videoframe/play_loop_mode/) | กำหนดว่า video จะวนซ้ำหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`hide_at_showing`](/slides/python-net/th/aspose.slides/videoframe/hide_at_showing/) | กำหนดว่า VideoFrame ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`volume`](/slides/python-net/th/aspose.slides/videoframe/volume/) | คืนค่าหรือกำหนดระดับเสียงของ audio.<br/>            อ่าน/เขียน [`AudioVolumeMode`](/slides/python-net/th/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/th/aspose.slides/videoframe/volume_value/) | คืนค่าหรือกำหนดระดับเสียงของ video อย่างแม่นยำเป็นเปอร์เซ็นต์.<br/>             ค่าถูกแสดงเป็นเปอร์เซ็นต์จาก 0 ถึง 100. ใช้คุณสมบัตินี้<br/>             เพื่ออ่านหรือกำหนดค่าระดับเสียงที่ละเอียดกว่าระดับที่กำหนดไว้ล่วงหน้า<br/>             ผ่านคุณสมบัติ [`VideoFrame.volume`](/slides/python-net/th/aspose.slides/videoframe/volume).<br/>             อ่าน/เขียน **float**. |
| [`play_mode`](/slides/python-net/th/aspose.slides/videoframe/play_mode/) | คืนค่าหรือกำหนดโหมดการเล่นของ video.<br/>            อ่าน/เขียน [`VideoPlayModePreset`](/slides/python-net/th/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/th/aspose.slides/videoframe/full_screen_mode/) | กำหนดว่า video จะแสดงในโหมดเต็มหน้าจอหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`link_path_long`](/slides/python-net/th/aspose.slides/videoframe/link_path_long/) | คืนค่าหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame.<br/>            อ่าน/เขียน **str**. |
| [`embedded_video`](/slides/python-net/th/aspose.slides/videoframe/embedded_video/) | คืนค่าหรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังเอาไว้.<br/>            อ่าน/เขียน [`IVideo`](/slides/python-net/th/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/th/aspose.slides/videoframe/trim_from_start/) | เริ่มตัด [ms] |
| [`trim_from_end`](/slides/python-net/th/aspose.slides/videoframe/trim_from_end/) | สิ้นสุดตัด [ms] |
| [`caption_tracks`](/slides/python-net/th/aspose.slides/videoframe/caption_tracks/) | รับชุดของคำบรรยายปิดที่เชื่อมโยงกับ video frame.<br/>             คุณสมบัตินี้เป็นอ่านอย่างเดียวและคืนค่า [`ICaptionsCollection`](/slides/python-net/th/aspose.slides/icaptionscollection) ที่บรรจุตรัคของคำบรรยายทั้งหมด. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/videoframe/get_image/#) | คืนค่าภาพย่อของ shape.<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของ shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/videoframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/videoframe/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ตัวกำหนดตำแหน่ง. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/videoframe/add_placeholder/#iplaceholder) | เพิ่มตัวกำหนดตำแหน่งใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวกำหนดตำแหน่งให้เป็นค่าที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/videoframe/get_base_placeholder/#) | คืนค่า shape ตัวกำหนดตำแหน่งพื้นฐาน (shape จากเลเอาต์และ/หรือสไลด์แม่ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/videoframe/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/videoframe/get_geometry_paths/#) | คืนค่าคัดลอกของเส้นทางของ shape เรขาคณิต. พิกัดเป็นสัมพันธ์กับมุมซ้ายบนของ shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | อัปเดตรูปทรงเรขาคณิตของ shape จากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องเป็นสัมพันธ์กับมุมซ้ายบนของ shape.<br/>            เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | อัปเดตรูปทรงเรขาคณิตของ shape จากอาร์เรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องเป็นสัมพันธ์กับมุมซ้ายบนของ shape.<br/>            เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/videoframe/create_shape_elements/#) | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของ shape. |

### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`VideoFrame`](/slides/python-net/th/aspose.slides/videoframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)