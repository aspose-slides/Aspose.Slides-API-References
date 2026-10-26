---
title: IAudioFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iaudioframe/
---
## IAudioFrame lớp

Biểu diễn một đoạn âm thanh trên slide.

Kiểu IAudioFrame cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/vi/aspose.slides/iaudioframe/audio_cd_start_track/) | Trả về hoặc đặt chỉ số track bắt đầu.<br/>            Read/write **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/vi/aspose.slides/iaudioframe/audio_cd_start_track_time/) | Trả về hoặc đặt thời gian track bắt đầu.<br/>            Read/write **int**. |
| [`audio_cd_end_track`](/slides/python-net/vi/aspose.slides/iaudioframe/audio_cd_end_track/) | Trả về hoặc đặt chỉ số track cuối cùng<br/>            Read/write **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/vi/aspose.slides/iaudioframe/audio_cd_end_track_time/) | Trả về hoặc đặt thời gian track cuối cùng.<br/>            Read/write **int**. |
| [`volume`](/slides/python-net/vi/aspose.slides/iaudioframe/volume/) | Trả về hoặc đặt âm lượng âm thanh.<br/>            Read/write [`AudioVolumeMode`](/slides/python-net/vi/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/vi/aspose.slides/iaudioframe/play_mode/) | Trả về hoặc đặt chế độ phát âm thanh.<br/>            Read/write [`AudioPlayModePreset`](/slides/python-net/vi/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/vi/aspose.slides/iaudioframe/hide_at_showing/) | Xác định xem AudioFrame có bị ẩn hay không.<br/>            Read/write **bool**. |
| [`play_loop_mode`](/slides/python-net/vi/aspose.slides/iaudioframe/play_loop_mode/) | Xác định xem âm thanh có được lặp lại hay không.<br/>            Read/write **bool**. |
| [`play_across_slides`](/slides/python-net/vi/aspose.slides/iaudioframe/play_across_slides/) | Xác định xem âm thanh có phát xuyên suốt các slide hay không.<br/>             Read/write **bool**. |
| [`rewind_audio`](/slides/python-net/vi/aspose.slides/iaudioframe/rewind_audio/) | Xác định xem âm thanh có tự động quay lại đầu sau khi phát hay không.<br/>             Read/write **bool**. |
| [`embedded`](/slides/python-net/vi/aspose.slides/iaudioframe/embedded/) | Xác định xem âm thanh có được nhúng vào bài thuyết trình hay không.<br/>            Read-only **bool**. |
| [`link_path_long`](/slides/python-net/vi/aspose.slides/iaudioframe/link_path_long/) | Trả về hoặc đặt tên tệp âm thanh được liên kết với AudioFrame.<br/>            Read/write **str**. |
| [`embedded_audio`](/slides/python-net/vi/aspose.slides/iaudioframe/embedded_audio/) | Trả về hoặc đặt đối tượng âm thanh được nhúng.<br/>            Read/write [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/vi/aspose.slides/iaudioframe/fade_in_duration/) | Xác định thời lượng (ms) cho hiệu ứng fade-in ban đầu của media.<br/>             Read/write **float**. |
| [`fade_out_duration`](/slides/python-net/vi/aspose.slides/iaudioframe/fade_out_duration/) | Xác định thời lượng (ms) cho hiệu ứng fade-out cuối cùng của media.<br/>             Read/write **float**. |
| [`volume_value`](/slides/python-net/vi/aspose.slides/iaudioframe/volume_value/) | Trả về hoặc đặt âm lượng âm thanh theo phần trăm.<br/>             Read/write **float**. |
| [`trim_from_start`](/slides/python-net/vi/aspose.slides/iaudioframe/trim_from_start/) | Xác định thời lượng (ms) sẽ bị loại bỏ từ đầu media trong quá trình phát.<br/>            Read/write **float**. |
| [`trim_from_end`](/slides/python-net/vi/aspose.slides/iaudioframe/trim_from_end/) | Xác định thời lượng (ms) sẽ bị loại bỏ từ cuối media trong quá trình phát.<br/>            Read/write **float**. |
| [`caption_tracks`](/slides/python-net/vi/aspose.slides/iaudioframe/caption_tracks/) | Lấy bộ sưu tập phụ đề đóng liên quan tới audio frame.<br/>            Thuộc tính này chỉ đọc và trả về một [`ICaptionsCollection`](/slides/python-net/vi/aspose.slides/icaptionscollection) chứa tất cả các track phụ đề. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/vi/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/vi/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/vi/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/vi/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/vi/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/vi/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/vi/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/vi/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/vi/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/vi/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/vi/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/vi/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/vi/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/vi/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/vi/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/vi/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/vi/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/vi/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/vi/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/vi/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/vi/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/vi/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)