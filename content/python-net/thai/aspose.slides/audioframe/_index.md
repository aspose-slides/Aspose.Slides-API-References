---
title: AudioFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/audioframe/
---
## AudioFrame คลาส

Represents an audio clip on a slide.

**การสืบทอด:**[`AudioFrame`](/slides/python-net/th/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/audioframe/is_text_holder/) | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/audioframe/placeholder/) | คืนค่าตัวแทนสำหรับรูปร่าง. คืนค่า None หากรูปร่างไม่มีตัวแทน.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/audioframe/custom_data/) | คืนค่าข้อมูลกำหนดเองของรูปร่าง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/audioframe/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติกรอบรูปดิบของรูปร่าง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/audioframe/frame/) | คืนค่า หรือกำหนดคุณสมบัติกรอบรูปของรูปร่าง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/audioframe/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่รวมคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/audioframe/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/audioframe/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่รวมเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/audioframe/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่รวมคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/audioframe/hyperlink_click/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/audioframe/hyperlink_mouse_over/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์ชี้.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/audioframe/hyperlink_manager/) | คืนค่าเมเนเจอร์ไฮเปอร์ลิงก์.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/audioframe/hidden/) | กำหนดว่ารูปร่างถูกซ่อนไว้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/audioframe/z_order_position/) | คืนตำแหน่งของรูปร่างในลำดับ z.<br/>            Shapes[0] คืนค่ารูปร่างที่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่ด้านหน้า ของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/audioframe/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/audioframe/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบ<br/>            แกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบ<br/>            บ่งบอกการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/audioframe/x/) | รับ หรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/audioframe/y/) | รับ หรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/audioframe/width/) | รับ หรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/audioframe/height/) | รับ หรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/audioframe/black_white_mode/) | คุณสมบัตินี้ระบุวิธีการแสดงรูปร่างในโหมดแสดงผลสีขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/audioframe/unique_id/) | คืนค่าไอดีภายในที่กำหนดขอบเขตตามงานนำเสนอซึ่งตั้งใจให้ใช้โดยแอดออนหรือโค้ดอื่น.<br/>            เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, ไม่ควรถือว่า<br/>            เป็นคีย์ที่ไม่ซ้ำและคงที่.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/audioframe/office_interop_shape_id/) | คืนค่าไอดีที่ไม่ซ้ำและกำหนดขอบเขตตามสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากทุกที่ในเอกสารได้อย่างเชื่อถือ.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/audioframe/alternative_text/) | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/audioframe/alternative_text_title/) | คืนค่า หรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/audioframe/name/) | คืนค่า หรือกำหนดชื่อของรูปร่าง.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างถ้าจำเป็น.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/audioframe/is_decorative/) | รับ หรือกำหนดตัวเลือก 'ทำเครื่องหมายเป็นของตกแต่ง'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/audioframe/shape_lock/) | คืนค่าการล็อครูปร่าง.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/audioframe/is_grouped/) | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/audioframe/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปร่างอยู่ในกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/audioframe/slide/) | คืนค่าสไลด์พ่อแม่ของรูปร่าง.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/audioframe/presentation/) | คืนค่าการนำเสนอพ่อแม่ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/audioframe/shape_style/) | คืนค่าอ็อบเจ็กต์สไตล์ของรูปร่าง.<br/>            อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/audioframe/shape_type/) | คืนค่า หรือกำหนดประเภท AutoShape สำหรับ PictureFrame.<br/>            มีรายการทั้งหมดที่อนุญาตในชุด [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype), ยกเว้นเส้นทุกรูปแบบ:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/audioframe/adjustments/) | คืนค่าคอลเลกชันของค่าการปรับของรูปร่าง.<br/>            อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/th/aspose.slides/audioframe/picture_frame_lock/) | คืนค่าการล็อครูปร่าง.<br/>            อ่านอย่างเดียว [`IPictureFrameLock`](/slides/python-net/th/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/th/aspose.slides/audioframe/picture_format/) | คืนค่าอ็อบเจ็กต์ PictureFillFormat สำหรับกรอบรูป.<br/>            อ่านอย่างเดียว [`IPictureFillFormat`](/slides/python-net/th/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/th/aspose.slides/audioframe/relative_scale_height/) | คืนค่า หรือกำหนดสเกลความสูง (เทียบกับขนาดรูปต้นฉบับ) ของกรอบรูป. ค่า 1.0 เท่ากับ 100%.<br/>            อ่าน/เขียน **float**. |
| [`relative_scale_width`](/slides/python-net/th/aspose.slides/audioframe/relative_scale_width/) | คืนค่า หรือกำหนดสเกลความกว้าง (เทียบกับขนาดรูปต้นฉบับ) ของกรอบรูป. ค่า 1.0 เท่ากับ 100%.<br/>            อ่าน/เขียน **float**. |
| [`is_cameo`](/slides/python-net/th/aspose.slides/audioframe/is_cameo/) | กำหนดว่า PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`audio_cd_start_track`](/slides/python-net/th/aspose.slides/audioframe/audio_cd_start_track/) | คืนค่า หรือกำหนดดัชนีเริ่มต้นของแทร็ก.<br/>            อ่าน/เขียน **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/th/aspose.slides/audioframe/audio_cd_start_track_time/) | คืนค่า หรือกำหนดเวลาเริ่มต้นของแทร็ก.<br/>            อ่าน/เขียน **int**. |
| [`audio_cd_end_track`](/slides/python-net/th/aspose.slides/audioframe/audio_cd_end_track/) | คืนค่า หรือกำหนดดัชนีสุดท้ายของแทร็ก<br/>            อ่าน/เขียน **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/th/aspose.slides/audioframe/audio_cd_end_track_time/) | คืนค่า หรือกำหนดเวลาสุดท้ายของแทร็ก.<br/>            อ่าน/เขียน **int**. |
| [`volume`](/slides/python-net/th/aspose.slides/audioframe/volume/) | คืนค่า หรือกำหนดระดับเสียงของออดิโอ.<br/>            อ่าน/เขียน [`AudioVolumeMode`](/slides/python-net/th/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/th/aspose.slides/audioframe/play_mode/) | คืนค่า หรือกำหนดโหมดการเล่นออดิโอ.<br/>            อ่าน/เขียน [`AudioPlayModePreset`](/slides/python-net/th/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/th/aspose.slides/audioframe/hide_at_showing/) | กำหนดว่า AudioFrame ถูกซ่อนไว้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`play_loop_mode`](/slides/python-net/th/aspose.slides/audioframe/play_loop_mode/) | กำหนดว่าออดิโอวนซ้ำหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`play_across_slides`](/slides/python-net/th/aspose.slides/audioframe/play_across_slides/) | กำหนดว่าออดิโอกำลังเล่นข้ามสไลด์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`rewind_audio`](/slides/python-net/th/aspose.slides/audioframe/rewind_audio/) | กำหนดว่าออดิโอจะถูกรีไวนด์อัตโนมัติไปยังจุดเริ่มต้นหลังการเล่นหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`embedded`](/slides/python-net/th/aspose.slides/audioframe/embedded/) | กำหนดว่าเสียงฝังอยู่ในงานนำเสนอหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`link_path_long`](/slides/python-net/th/aspose.slides/audioframe/link_path_long/) | คืนค่า หรือกำหนดชื่อไฟล์ออดิโอที่เชื่อมโยงกับ AudioFrame.<br/>            อ่าน/เขียน **str**. |
| [`embedded_audio`](/slides/python-net/th/aspose.slides/audioframe/embedded_audio/) | คืนค่า หรือกำหนดอ็อบเจ็กต์ออดิโอฝัง.<br/>            อ่าน/เขียน [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/th/aspose.slides/audioframe/fade_in_duration/) | กำหนดระยะเวลาการค่อย ๆ ปรากฏครั้งแรกของสื่อเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`fade_out_duration`](/slides/python-net/th/aspose.slides/audioframe/fade_out_duration/) | กำหนดระยะเวลาการค่อย ๆ จางออกของสื่อเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`volume_value`](/slides/python-net/th/aspose.slides/audioframe/volume_value/) | คืนค่า หรือกำหนดระดับเสียงออดิโอเป็นเปอร์เซ็นต์.<br/>            อ่าน/เขียน **float**. |
| [`trim_from_start`](/slides/python-net/th/aspose.slides/audioframe/trim_from_start/) | กำหนดระยะเวลาที่จะลบออกจากส่วนเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`trim_from_end`](/slides/python-net/th/aspose.slides/audioframe/trim_from_end/) | กำหนดระยะเวลาที่จะลบออกจากส่วนสุดท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`caption_tracks`](/slides/python-net/th/aspose.slides/audioframe/caption_tracks/) | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับเฟรมออดิโอ.<br/>            คุณสมบัตินี้เป็นอ่านอย่างเดียวและคืนค่า [`ICaptionsCollection`](/slides/python-net/th/aspose.slides/icaptionscollection) ที่บรรจุตร็กทั้งหมดของคำบรรยาย. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/audioframe/get_image/#) | คืนค่าภาพย่อของรูปร่าง.<br/>            ShapeThumbnailBounds.Shape เป็นประเภทค่าขอบเขตภาพย่อของรูปร่างที่ใช้โดยค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของรูปร่าง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/audioframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/audioframe/remove_placeholder/#) | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/audioframe/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ตามที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/audioframe/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดจาก).<br/>            คืนค่า None หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/audioframe/get_visual_bounds/#) | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/audioframe/get_geometry_paths/#) | คืนค่าสำเนาของพาธของรูปร่างเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้าย<br/>             บนของรูปร่าง.<br/>             เปลี่ยนประเภทของรูปร่าง ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้าย<br/>             บนของรูปร่าง.<br/>             เปลี่ยนประเภทของรูปร่าง ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/audioframe/create_shape_elements/#) | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของรูปร่าง. |

### ดูเพิ่มเติม
* คลาส [`AudioFrame`](/slides/python-net/th/aspose.slides/audioframe)
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)