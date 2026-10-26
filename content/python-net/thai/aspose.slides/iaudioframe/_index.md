---
title: IAudioFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iaudioframe/
---
## IAudioFrame คลาส

แสดงถึงคลิปเสียงบนสไลด์

ประเภท IAudioFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/th/aspose.slides/iaudioframe/audio_cd_start_track/) | คืนค่า หรือกำหนดดัชนีแทร็กเริ่มต้น.<br/>            อ่าน/เขียน **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/th/aspose.slides/iaudioframe/audio_cd_start_track_time/) | คืนค่า หรือกำหนดเวลาเริ่มต้นของแทร็ก.<br/>            อ่าน/เขียน **int**. |
| [`audio_cd_end_track`](/slides/python-net/th/aspose.slides/iaudioframe/audio_cd_end_track/) | คืนค่า หรือกำหนดดัชนีแทร็กสุดท้าย<br/>            อ่าน/เขียน **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/th/aspose.slides/iaudioframe/audio_cd_end_track_time/) | คืนค่า หรือกำหนดเวลาสิ้นสุดของแทร็ก.<br/>            อ่าน/เขียน **int**. |
| [`volume`](/slides/python-net/th/aspose.slides/iaudioframe/volume/) | คืนค่า หรือกำหนดระดับเสียง.<br/>            อ่าน/เขียน [`AudioVolumeMode`](/slides/python-net/th/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/th/aspose.slides/iaudioframe/play_mode/) | คืนค่า หรือกำหนดโหมดการเล่นเสียง.<br/>            อ่าน/เขียน [`AudioPlayModePreset`](/slides/python-net/th/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/th/aspose.slides/iaudioframe/hide_at_showing/) | กำหนดว่า AudioFrame ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`play_loop_mode`](/slides/python-net/th/aspose.slides/iaudioframe/play_loop_mode/) | กำหนดว่าเสียงถูกวนซ้ำหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`play_across_slides`](/slides/python-net/th/aspose.slides/iaudioframe/play_across_slides/) | กำหนดว่าเสียงกำลังเล่นต่อเนื่องระหว่างสไลด์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`rewind_audio`](/slides/python-net/th/aspose.slides/iaudioframe/rewind_audio/) | กำหนดว่าเสียงจะถูกรีวินด์กลับไปที่จุดเริ่มต้นโดยอัตโนมัติหลังจากเล่นหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`embedded`](/slides/python-net/th/aspose.slides/iaudioframe/embedded/) | กำหนดว่าเสียงถูกฝังในงานนำเสนอหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`link_path_long`](/slides/python-net/th/aspose.slides/iaudioframe/link_path_long/) | คืนค่า หรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame.<br/>            อ่าน/เขียน **str**. |
| [`embedded_audio`](/slides/python-net/th/aspose.slides/iaudioframe/embedded_audio/) | คืนค่า หรือกำหนดอ็อบเจกต์เสียงที่ฝังไว้.<br/>            อ่าน/เขียน [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/th/aspose.slides/iaudioframe/fade_in_duration/) | ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`fade_out_duration`](/slides/python-net/th/aspose.slides/iaudioframe/fade_out_duration/) | ระบุระยะเวลาการเฟดเอาต์สุดท้ายของสื่อเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`volume_value`](/slides/python-net/th/aspose.slides/iaudioframe/volume_value/) | คืนค่า หรือกำหนดระดับเสียงเป็นเปอร์เซ็นต์.<br/>            อ่าน/เขียน **float**. |
| [`trim_from_start`](/slides/python-net/th/aspose.slides/iaudioframe/trim_from_start/) | ระบุระยะเวลาที่จะตัดออกจากจุดเริ่มต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`trim_from_end`](/slides/python-net/th/aspose.slides/iaudioframe/trim_from_end/) | ระบุระยะเวลาที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที.<br/>            อ่าน/เขียน **float**. |
| [`caption_tracks`](/slides/python-net/th/aspose.slides/iaudioframe/caption_tracks/) | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ audio frame.<br/>            คุณสมบัตินี้อ่านอย่างเดียวและคืนค่า [`ICaptionsCollection`](/slides/python-net/th/aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/th/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/th/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/th/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/th/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/th/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/th/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/th/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/th/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/th/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/th/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/th/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/th/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/th/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/th/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/th/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/th/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/th/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/th/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/th/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/th/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/th/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/th/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)