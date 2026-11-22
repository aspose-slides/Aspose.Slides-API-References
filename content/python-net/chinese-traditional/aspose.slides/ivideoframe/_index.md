---
title: IVideoFrame class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ivideoframe/
---
## IVideoFrame 類別

代表投影片上的影片剪輯。

IVideoFrame 型別公開以下成員：

## 屬性

| Property | 說明 |
| :- | :- |
| [`rewind_video`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/rewind_video/) | 判斷是否在影片播放完畢後自動倒回至開始<br/>            一旦影片播放完畢。<br/>            讀寫 **bool**. |
| [`play_loop_mode`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/play_loop_mode/) | 判斷是否循環播放影片。<br/>            讀寫 **bool**. |
| [`hide_at_showing`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/hide_at_showing/) | 判斷 VideoFrame 是否隱藏。<br/>            讀寫 **bool**. |
| [`volume`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/volume/) | 取得或設定音訊音量。<br/>            讀寫 [`AudioVolumeMode`](/slides/python-net/zh-hant/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/volume_value/) | 取得或設定精確的影片音量（百分比）。<br/>            該值以 0 到 100 的百分比表示。使用此屬性<br/>            讀取或設定比 [`IVideoFrame.volume`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/volume) 屬性中預設等級更精確的音量值。<br/>            讀寫 **float**. |
| [`play_mode`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/play_mode/) | 取得或設定影片播放模式。<br/>            讀寫 [`VideoPlayModePreset`](/slides/python-net/zh-hant/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/full_screen_mode/) | 判斷影片是否以全螢幕模式顯示。<br/>            讀寫 **bool**. |
| [`link_path_long`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/link_path_long/) | 取得或設定連結至 VideoFrame 的影片檔案名稱。<br/>            讀寫 **str**. |
| [`embedded_video`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/embedded_video/) | 取得或設定嵌入式影片物件。<br/>            讀寫 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/trim_from_start/) | 剪裁起始點 [ms] |
| [`trim_from_end`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/trim_from_end/) | 剪裁終止點 [ms] |
| [`caption_tracks`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/caption_tracks/) | 取得與音訊框架相關的閉幕字幕集合。<br/>            此屬性為唯讀，並返回包含所有字幕軌道的 [`ICaptionsCollection`](/slides/python-net/zh-hant/aspose.slides/icaptionscollection). |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/raw_frame/) |  |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/frame/) |  |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/fill_format/) |  |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/rotation/) |  |
| [`x`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/x/) |  |
| [`y`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/y/) |  |
| [`width`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/width/) |  |
| [`height`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/height/) |  |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/name/) |  |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/parent_group/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/hyperlink_manager/) |  |

## 方法

| Method | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/ivideoframe/get_base_placeholder/#) |  |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)