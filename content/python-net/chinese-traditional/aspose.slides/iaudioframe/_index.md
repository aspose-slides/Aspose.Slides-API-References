---
title: IAudioFrame class
second_title: Aspose.Slides 用於 Python（透過 .NET）API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iaudioframe/
---
## IAudioFrame 類別

代表投影片上的音訊剪輯。

IAudioFrame 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/audio_cd_start_track/) | 傳回或設定起始軌道索引。<br/>            讀/寫 **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/audio_cd_start_track_time/) | 傳回或設定起始軌道時間。<br/>            讀/寫 **int**. |
| [`audio_cd_end_track`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/audio_cd_end_track/) | 傳回或設定最後軌道索引<br/>            讀/寫 **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/audio_cd_end_track_time/) | 傳回或設定最後軌道時間。<br/>            讀/寫 **int**. |
| [`volume`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/volume/) | 傳回或設定音訊音量。<br/>            讀/寫 [`AudioVolumeMode`](/slides/python-net/zh-hant/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/play_mode/) | 傳回或設定音訊播放模式。<br/>            讀/寫 [`AudioPlayModePreset`](/slides/python-net/zh-hant/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/hide_at_showing/) | 判斷 AudioFrame 是否隱藏。<br/>            讀/寫 **bool**. |
| [`play_loop_mode`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/play_loop_mode/) | 判斷音訊是否循環播放。<br/>            讀/寫 **bool**. |
| [`play_across_slides`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/play_across_slides/) | 判斷音訊是否跨投影片播放。<br/>             讀/寫 **bool**. |
| [`rewind_audio`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/rewind_audio/) | 判斷音訊在播放完畢後是否自動倒回至開頭。<br/>             讀/寫 **bool**. |
| [`embedded`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/embedded/) | 判斷音訊是否已嵌入至簡報。<br/>            唯讀 **bool**. |
| [`link_path_long`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/link_path_long/) | 傳回或設定連結至 AudioFrame 的音訊檔案名稱。<br/>            讀/寫 **str**. |
| [`embedded_audio`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/embedded_audio/) | 傳回或設定嵌入的音訊物件。<br/>            讀/寫 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/fade_in_duration/) | 指定媒體初始淡入的持續時間（毫秒）。<br/>             讀/寫 **float**. |
| [`fade_out_duration`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/fade_out_duration/) | 指定媒體結束淡出的持續時間（毫秒）。<br/>             讀/寫 **float**. |
| [`volume_value`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/volume_value/) | 傳回或設定音訊音量（百分比）。<br/>             讀/寫 **float**. |
| [`trim_from_start`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/trim_from_start/) | 指定在播放期間從媒體開頭移除的時間長度（毫秒）。<br/>            讀/寫 **float**. |
| [`trim_from_end`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/trim_from_end/) | 指定在播放期間從媒體結尾移除的時間長度（毫秒）。<br/>            讀/寫 **float**. |
| [`caption_tracks`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/caption_tracks/) | 取得與音訊框架關聯的隱蔽字幕集合。<br/>            此屬性唯讀，且回傳一個 [`ICaptionsCollection`](/slides/python-net/zh-hant/aspose.slides/icaptionscollection)，其中包含所有字幕軌道。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)