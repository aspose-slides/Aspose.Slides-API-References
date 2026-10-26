---
title: IAudioFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iaudioframe/
---
## IAudioFrame クラス

スライド上のオーディオクリップを表します。

IAudioFrame 型は次のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/ja/aspose.slides/iaudioframe/audio_cd_start_track/) | 開始トラックインデックスを取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`audio_cd_start_track_time`](/slides/python-net/ja/aspose.slides/iaudioframe/audio_cd_start_track_time/) | 開始トラック時間を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`audio_cd_end_track`](/slides/python-net/ja/aspose.slides/iaudioframe/audio_cd_end_track/) | 最後のトラックインデックスを取得または設定します<br/>            読み取り/書き込み **int**。 |
| [`audio_cd_end_track_time`](/slides/python-net/ja/aspose.slides/iaudioframe/audio_cd_end_track_time/) | 最後のトラック時間を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`volume`](/slides/python-net/ja/aspose.slides/iaudioframe/volume/) | オーディオボリュームを取得または設定します。<br/>            読み取り/書き込み [`AudioVolumeMode`](/slides/python-net/ja/aspose.slides/audiovolumemode)。 |
| [`play_mode`](/slides/python-net/ja/aspose.slides/iaudioframe/play_mode/) | オーディオ再生モードを取得または設定します。<br/>            読み取り/書き込み [`AudioPlayModePreset`](/slides/python-net/ja/aspose.slides/audioplaymodepreset)。 |
| [`hide_at_showing`](/slides/python-net/ja/aspose.slides/iaudioframe/hide_at_showing/) | AudioFrame が非表示かどうかを判定します。<br/>            読み取り/書き込み **bool**。 |
| [`play_loop_mode`](/slides/python-net/ja/aspose.slides/iaudioframe/play_loop_mode/) | オーディオがループ再生かどうかを判定します。<br/>            読み取り/書き込み **bool**。 |
| [`play_across_slides`](/slides/python-net/ja/aspose.slides/iaudioframe/play_across_slides/) | オーディオがスライド間で再生されるかどうかを判定します。<br/>            読み取り/書き込み **bool**。 |
| [`rewind_audio`](/slides/python-net/ja/aspose.slides/iaudioframe/rewind_audio/) | オーディオが再生後に自動的に先頭へ巻き戻されるかどうかを判定します。<br/>            読み取り/書き込み **bool**。 |
| [`embedded`](/slides/python-net/ja/aspose.slides/iaudioframe/embedded/) | サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。<br/>            読み取り専用 **bool**。 |
| [`link_path_long`](/slides/python-net/ja/aspose.slides/iaudioframe/link_path_long/) | AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`embedded_audio`](/slides/python-net/ja/aspose.slides/iaudioframe/embedded_audio/) | 埋め込みオーディオオブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)。 |
| [`fade_in_duration`](/slides/python-net/ja/aspose.slides/iaudioframe/fade_in_duration/) | メディアの初期フェードインの時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`fade_out_duration`](/slides/python-net/ja/aspose.slides/iaudioframe/fade_out_duration/) | メディアの終了フェードアウトの時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`volume_value`](/slides/python-net/ja/aspose.slides/iaudioframe/volume_value/) | オーディオボリューム（パーセント）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`trim_from_start`](/slides/python-net/ja/aspose.slides/iaudioframe/trim_from_start/) | 再生中にメディアの先頭から除去する時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`trim_from_end`](/slides/python-net/ja/aspose.slides/iaudioframe/trim_from_end/) | 再生中にメディアの末尾から除去する時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`caption_tracks`](/slides/python-net/ja/aspose.slides/iaudioframe/caption_tracks/) | オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。<br/>            このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](/slides/python-net/ja/aspose.slides/icaptionscollection) を返します。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/ja/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/ja/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/ja/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/ja/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/ja/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/ja/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/ja/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ja/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/ja/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/ja/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/ja/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ja/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/ja/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/ja/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ja/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/ja/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/ja/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/ja/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/ja/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/ja/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ja/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ja/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)