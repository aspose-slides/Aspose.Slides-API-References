---
title: IAudioFrame class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iaudioframe/
---
## IAudioFrame 클래스

슬라이드의 오디오 클립을 나타냅니다.

IAudioFrame 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/ko/aspose.slides/iaudioframe/audio_cd_start_track/) | Returns or sets a start track index.<br/>            읽기/쓰기 **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/ko/aspose.slides/iaudioframe/audio_cd_start_track_time/) | Returns or sets a start track time.<br/>            읽기/쓰기 **int**. |
| [`audio_cd_end_track`](/slides/python-net/ko/aspose.slides/iaudioframe/audio_cd_end_track/) | Returns or sets a last track index<br/>            읽기/쓰기 **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/ko/aspose.slides/iaudioframe/audio_cd_end_track_time/) | Returns or sets a last track time.<br/>            읽기/쓰기 **int**. |
| [`volume`](/slides/python-net/ko/aspose.slides/iaudioframe/volume/) | Returns or sets the audio volume.<br/>            읽기/쓰기 [`AudioVolumeMode`](/slides/python-net/ko/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ko/aspose.slides/iaudioframe/play_mode/) | Returns or sets the audio play mode.<br/>            읽기/쓰기 [`AudioPlayModePreset`](/slides/python-net/ko/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/ko/aspose.slides/iaudioframe/hide_at_showing/) | Determines whether an AudioFrame is hidden.<br/>            읽기/쓰기 **bool**. |
| [`play_loop_mode`](/slides/python-net/ko/aspose.slides/iaudioframe/play_loop_mode/) | Determines whether an audio is looped.<br/>            읽기/쓰기 **bool**. |
| [`play_across_slides`](/slides/python-net/ko/aspose.slides/iaudioframe/play_across_slides/) | Determines whether an audio is playing across the slides.<br/>            읽기/쓰기 **bool**. |
| [`rewind_audio`](/slides/python-net/ko/aspose.slides/iaudioframe/rewind_audio/) | Determines whether an audio is automatically rewinded to start after playing.<br/>            읽기/쓰기 **bool**. |
| [`embedded`](/slides/python-net/ko/aspose.slides/iaudioframe/embedded/) | Determines whether a sound is embedded to a presentation.<br/>            읽기 전용 **bool**. |
| [`link_path_long`](/slides/python-net/ko/aspose.slides/iaudioframe/link_path_long/) | Returns or sets the name of an audio file which is linked to an AudioFrame.<br/>            읽기/쓰기 **str**. |
| [`embedded_audio`](/slides/python-net/ko/aspose.slides/iaudioframe/embedded_audio/) | Returns or sets embedded audio object.<br/>            읽기/쓰기 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/ko/aspose.slides/iaudioframe/fade_in_duration/) | Specifies the time duration for the initial fade-in of the media in milliseconds.<br/>            읽기/쓰기 **float**. |
| [`fade_out_duration`](/slides/python-net/ko/aspose.slides/iaudioframe/fade_out_duration/) | Specifies the time duration for the ending fade-out of the media in milliseconds.<br/>            읽기/쓰기 **float**. |
| [`volume_value`](/slides/python-net/ko/aspose.slides/iaudioframe/volume_value/) | Returns or sets the audio volume in percents.<br/>            읽기/쓰기 **float**. |
| [`trim_from_start`](/slides/python-net/ko/aspose.slides/iaudioframe/trim_from_start/) | Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds.<br/>            읽기/쓰기 **float**. |
| [`trim_from_end`](/slides/python-net/ko/aspose.slides/iaudioframe/trim_from_end/) | Specifies the time duration to be removed from the end of the media during playback, in milliseconds.<br/>            읽기/쓰기 **float**. |
| [`caption_tracks`](/slides/python-net/ko/aspose.slides/iaudioframe/caption_tracks/) | Gets the collection of closed captions associated with the audio frame.<br/>            이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [`ICaptionsCollection`](/slides/python-net/ko/aspose.slides/icaptionscollection)를 반환합니다. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/ko/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/ko/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/ko/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/ko/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/ko/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/ko/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/ko/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ko/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ko/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/ko/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/ko/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ko/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/ko/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/ko/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/ko/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ko/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/ko/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/ko/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/ko/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/ko/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/ko/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/ko/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ko/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ko/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ko/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/ko/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ko/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ko/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ko/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)