---
title: IVideoFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ivideoframe/
---
## IVideoFrame คลาส

แสดงคลิปวิดีโอบนสไลด์.

ประเภท IVideoFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`rewind_video`](/slides/python-net/th/aspose.slides/ivideoframe/rewind_video/) | กำหนดว่าวิดีโอจะถูกตั้งค่าให้กลับไปเริ่มต้นโดยอัตโนมัติหรือไม่<br/>            ทันทีที่ภาพยนต์เล่นจบลง.<br/>            อ่าน/เขียน **bool**. |
| [`play_loop_mode`](/slides/python-net/th/aspose.slides/ivideoframe/play_loop_mode/) | กำหนดว่าวิดีโอจะทำการวนซ้ำหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`hide_at_showing`](/slides/python-net/th/aspose.slides/ivideoframe/hide_at_showing/) | กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`volume`](/slides/python-net/th/aspose.slides/ivideoframe/volume/) | คืนหรือกำหนดระดับเสียงของออดิโอ.<br/>            อ่าน/เขียน [`AudioVolumeMode`](/slides/python-net/th/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/th/aspose.slides/ivideoframe/volume_value/) | คืนหรือกำหนดระดับเสียงวิดีโอที่แม่นยำเป็นเปอร์เซ็นต์.<br/>            ค่าแสดงเป็นเปอร์เซ็นต์จาก 0 ถึง 100. ใช้คุณลักษณะนี้<br/>            เพื่ออ่านหรือกำหนดค่าระดับเสียงที่แม่นยำกว่าระดับที่กำหนดไว้ล่วงหน้า<br/>            ที่มีให้ผ่านคุณลักษณะ [`IVideoFrame.volume`](/slides/python-net/th/aspose.slides/ivideoframe/volume).<br/>            อ่าน/เขียน **float**. |
| [`play_mode`](/slides/python-net/th/aspose.slides/ivideoframe/play_mode/) | คืนหรือกำหนดโหมดการเล่นวิดีโอ.<br/>            อ่าน/เขียน [`VideoPlayModePreset`](/slides/python-net/th/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/th/aspose.slides/ivideoframe/full_screen_mode/) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มจอหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`link_path_long`](/slides/python-net/th/aspose.slides/ivideoframe/link_path_long/) | คืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame.<br/>            อ่าน/เขียน **str**. |
| [`embedded_video`](/slides/python-net/th/aspose.slides/ivideoframe/embedded_video/) | คืนหรือกำหนดวัตถุวิดีโอฝังตัว.<br/>            อ่าน/เขียน [`IVideo`](/slides/python-net/th/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/th/aspose.slides/ivideoframe/trim_from_start/) | จุดเริ่มต้นการตัด [ms] |
| [`trim_from_end`](/slides/python-net/th/aspose.slides/ivideoframe/trim_from_end/) | จุดสิ้นสุดการตัด [ms] |
| [`caption_tracks`](/slides/python-net/th/aspose.slides/ivideoframe/caption_tracks/) | รับชุดของคำบรรยายปิดที่เชื่อมโยงกับเฟรมออดิโอ.<br/>            คุณลักษณะนี้เป็นแบบอ่านอย่างเดียวและคืนค่า [`ICaptionsCollection`](/slides/python-net/th/aspose.slides/icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/ivideoframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/th/aspose.slides/ivideoframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/th/aspose.slides/ivideoframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/th/aspose.slides/ivideoframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/th/aspose.slides/ivideoframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/th/aspose.slides/ivideoframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/th/aspose.slides/ivideoframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/th/aspose.slides/ivideoframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/ivideoframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/th/aspose.slides/ivideoframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/ivideoframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/th/aspose.slides/ivideoframe/raw_frame/) |  |
| [`frame`](/slides/python-net/th/aspose.slides/ivideoframe/frame/) |  |
| [`line_format`](/slides/python-net/th/aspose.slides/ivideoframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/th/aspose.slides/ivideoframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides/ivideoframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides/ivideoframe/fill_format/) |  |
| [`hidden`](/slides/python-net/th/aspose.slides/ivideoframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/th/aspose.slides/ivideoframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/ivideoframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/th/aspose.slides/ivideoframe/rotation/) |  |
| [`x`](/slides/python-net/th/aspose.slides/ivideoframe/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides/ivideoframe/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides/ivideoframe/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides/ivideoframe/height/) |  |
| [`alternative_text`](/slides/python-net/th/aspose.slides/ivideoframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/ivideoframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/th/aspose.slides/ivideoframe/name/) |  |
| [`is_decorative`](/slides/python-net/th/aspose.slides/ivideoframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/th/aspose.slides/ivideoframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/ivideoframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/th/aspose.slides/ivideoframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/ivideoframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/th/aspose.slides/ivideoframe/parent_group/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/ivideoframe/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/ivideoframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/ivideoframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/ivideoframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/ivideoframe/hyperlink_manager/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/ivideoframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/ivideoframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/ivideoframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/ivideoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/ivideoframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/ivideoframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/ivideoframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/ivideoframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/ivideoframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/ivideoframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/ivideoframe/get_base_placeholder/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)