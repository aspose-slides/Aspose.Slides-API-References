---
title: IAudioFrame class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iaudioframe/
---
## IAudioFrame 类

表示幻灯片上的音频剪辑。

IAudioFrame 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/zh/aspose.slides/iaudioframe/audio_cd_start_track/) | 返回或设置起始轨道索引。<br/>            读/写 **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/zh/aspose.slides/iaudioframe/audio_cd_start_track_time/) | 返回或设置起始轨道时间。<br/>            读/写 **int**. |
| [`audio_cd_end_track`](/slides/python-net/zh/aspose.slides/iaudioframe/audio_cd_end_track/) | 返回或设置最后轨道索引。<br/>            读/写 **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/zh/aspose.slides/iaudioframe/audio_cd_end_track_time/) | 返回或设置最后轨道时间。<br/>            读/写 **int**. |
| [`volume`](/slides/python-net/zh/aspose.slides/iaudioframe/volume/) | 返回或设置音频音量。<br/>            读/写 [`AudioVolumeMode`](/slides/python-net/zh/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/zh/aspose.slides/iaudioframe/play_mode/) | 返回或设置音频播放模式。<br/>            读/写 [`AudioPlayModePreset`](/slides/python-net/zh/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/zh/aspose.slides/iaudioframe/hide_at_showing/) | 确定 AudioFrame 是否隐藏。<br/>            读/写 **bool**. |
| [`play_loop_mode`](/slides/python-net/zh/aspose.slides/iaudioframe/play_loop_mode/) | 确定音频是否循环。<br/>            读/写 **bool**. |
| [`play_across_slides`](/slides/python-net/zh/aspose.slides/iaudioframe/play_across_slides/) | 确定音频是否在幻灯片之间播放。<br/>            读/写 **bool**. |
| [`rewind_audio`](/slides/python-net/zh/aspose.slides/iaudioframe/rewind_audio/) | 确定音频在播放后是否自动倒回到起始位置。<br/>            读/写 **bool**. |
| [`embedded`](/slides/python-net/zh/aspose.slides/iaudioframe/embedded/) | 确定声音是否嵌入到演示文稿中。<br/>            只读 **bool**. |
| [`link_path_long`](/slides/python-net/zh/aspose.slides/iaudioframe/link_path_long/) | 返回或设置链接到 AudioFrame 的音频文件名称。<br/>            读/写 **str**. |
| [`embedded_audio`](/slides/python-net/zh/aspose.slides/iaudioframe/embedded_audio/) | 返回或设置嵌入的音频对象。<br/>            读/写 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/zh/aspose.slides/iaudioframe/fade_in_duration/) | 指定媒体初始淡入的时间持续量（毫秒）。<br/>            读/写 **float**. |
| [`fade_out_duration`](/slides/python-net/zh/aspose.slides/iaudioframe/fade_out_duration/) | 指定媒体结束淡出的时间持续量（毫秒）。<br/>            读/写 **float**. |
| [`volume_value`](/slides/python-net/zh/aspose.slides/iaudioframe/volume_value/) | 返回或设置音频音量（百分比）。<br/>            读/写 **float**. |
| [`trim_from_start`](/slides/python-net/zh/aspose.slides/iaudioframe/trim_from_start/) | 指定播放期间从媒体开头删除的时间持续量（毫秒）。<br/>            读/写 **float**. |
| [`trim_from_end`](/slides/python-net/zh/aspose.slides/iaudioframe/trim_from_end/) | 指定播放期间从媒体结尾删除的时间持续量（毫秒）。<br/>            读/写 **float**. |
| [`caption_tracks`](/slides/python-net/zh/aspose.slides/iaudioframe/caption_tracks/) | 获取与音频帧关联的闭字幕集合。<br/>            此属性为只读，返回包含所有字幕轨道的 [`ICaptionsCollection`](/slides/python-net/zh/aspose.slides/icaptionscollection). |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/zh/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/zh/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/zh/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/zh/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/zh/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/zh/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/zh/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/zh/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/zh/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/zh/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/zh/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/zh/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/zh/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/zh/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/zh/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/zh/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/zh/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)