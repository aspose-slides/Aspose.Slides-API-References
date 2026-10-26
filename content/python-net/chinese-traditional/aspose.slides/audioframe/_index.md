---
title: AudioFrame class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/audioframe/
---
## AudioFrame 類別

Represents an audio clip on a slide.

**Inheritance:**[`AudioFrame`](/slides/python-net/zh-hant/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The AudioFrame type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/audioframe/is_text_holder/) | 確定形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/audioframe/placeholder/) | 傳回形狀的佔位符。如果形狀沒有佔位符，則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/audioframe/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/audioframe/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/audioframe/frame/) | 傳回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/audioframe/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/audioframe/three_d_format/) | 傳回形狀的 3d 效果屬性的 ThreeDFormat 物件。<br/>            註：對於某些沒有 3d 屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/audioframe/effect_format/) | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/audioframe/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/audioframe/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/audioframe/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/audioframe/hyperlink_manager/) | 傳回超連結管理員。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/audioframe/hidden/) | 確定形狀是否隱藏。<br/>            讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/audioframe/z_order_position/) | 傳回形狀在 Z 軸排序中的位置。<br/>            Shapes[0] 傳回 Z 軸排序最靠後的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回最前面的形狀。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/audioframe/connection_site_count/) | 傳回形狀的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/audioframe/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/audioframe/x/) | 取得或設定形狀左上角的 X 座標，以點為單位。<br/>            讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/audioframe/y/) | 取得或設定形狀左上角的 Y 座標，以點為單位。<br/>            讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/audioframe/width/) | 取得或設定形狀的寬度，以點為單位。<br/>            讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/audioframe/height/) | 取得或設定形狀的高度，以點為單位。<br/>            讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/audioframe/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/audioframe/unique_id/) | 傳回供外掛或其他程式使用的內部、簡報範圍的識別碼。<br/>            由於此值可被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/audioframe/office_interop_shape_id/) | 傳回在簡報生命週期內保持不變的投影片範圍唯一識別碼，可讓 PowerPoint 或互操作程式從文件任何位置可靠參照形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/audioframe/alternative_text/) | 傳回或設定與形狀關聯的替代文字。<br/>            讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/audioframe/alternative_text_title/) | 傳回或設定與形狀關聯的替代文字標題。<br/>            讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/audioframe/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。如有需要請使用空字串。<br/>            讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/audioframe/is_decorative/) | 取得或設定「標記為裝飾」選項。<br/>            讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/audioframe/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IPictureFrameLock`](/slides/python-net/zh-hant/aspose.slides/ipictureframelock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/audioframe/is_grouped/) | 確定形狀是否已分組。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/audioframe/parent_group/) | 傳回如果形狀已分組則為其父層 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/audioframe/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/audioframe/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/audioframe/shape_style/) | 傳回形狀的樣式物件。<br/>            唯讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/audioframe/shape_type/) | 傳回或設定 PictureFrame 的 AutoShape 類型。<br/>            可接受的項目皆屬於集合 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)，<br/>            但以下各種線條除外：<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/audioframe/adjustments/) | 傳回形狀的調整值集合。<br/>            唯讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection)。 |
| [`picture_frame_lock`](/slides/python-net/zh-hant/aspose.slides/audioframe/picture_frame_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IPictureFrameLock`](/slides/python-net/zh-hant/aspose.slides/ipictureframelock)。 |
| [`picture_format`](/slides/python-net/zh-hant/aspose.slides/audioframe/picture_format/) | 傳回圖片框的 PictureFillFormat 物件。<br/>            唯讀 [`IPictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat)。 |
| [`relative_scale_height`](/slides/python-net/zh-hant/aspose.slides/audioframe/relative_scale_height/) | 傳回或設定圖片框高度的比例（相對於原始圖片大小）。值 1.0 對應 100%。<br/>            讀寫 **float**。 |
| [`relative_scale_width`](/slides/python-net/zh-hant/aspose.slides/audioframe/relative_scale_width/) | 傳回或設定圖片框寬度的比例（相對於原始圖片大小）。值 1.0 對應 100%。<br/>            讀寫 **float**。 |
| [`is_cameo`](/slides/python-net/zh-hant/aspose.slides/audioframe/is_cameo/) | 確定 PictureFrame 是否為 Cameo 物件。<br/>            唯讀 **bool**。 |
| [`audio_cd_start_track`](/slides/python-net/zh-hant/aspose.slides/audioframe/audio_cd_start_track/) | 傳回或設定起始軌道索引。<br/>            讀寫 **int**。 |
| [`audio_cd_start_track_time`](/slides/python-net/zh-hant/aspose.slides/audioframe/audio_cd_start_track_time/) | 傳回或設定起始軌道時間。<br/>            讀寫 **int**。 |
| [`audio_cd_end_track`](/slides/python-net/zh-hant/aspose.slides/audioframe/audio_cd_end_track/) | 傳回或設定最後軌道索引。<br/>            讀寫 **int**。 |
| [`audio_cd_end_track_time`](/slides/python-net/zh-hant/aspose.slides/audioframe/audio_cd_end_track_time/) | 傳回或設定最後軌道時間。<br/>            讀寫 **int**。 |
| [`volume`](/slides/python-net/zh-hant/aspose.slides/audioframe/volume/) | 傳回或設定音訊音量。<br/>            讀寫 [`AudioVolumeMode`](/slides/python-net/zh-hant/aspose.slides/audiovolumemode)。 |
| [`play_mode`](/slides/python-net/zh-hant/aspose.slides/audioframe/play_mode/) | 傳回或設定音訊播放模式。<br/>            讀寫 [`AudioPlayModePreset`](/slides/python-net/zh-hant/aspose.slides/audioplaymodepreset)。 |
| [`hide_at_showing`](/slides/python-net/zh-hant/aspose.slides/audioframe/hide_at_showing/) | 確定音訊是否隱藏。<br/>            讀寫 **bool**。 |
| [`play_loop_mode`](/slides/python-net/zh-hant/aspose.slides/audioframe/play_loop_mode/) | 確定音訊是否循環播放。<br/>            讀寫 **bool**。 |
| [`play_across_slides`](/slides/python-net/zh-hant/aspose.slides/audioframe/play_across_slides/) | 確定音訊是否跨投影片播放。<br/>            讀寫 **bool**。 |
| [`rewind_audio`](/slides/python-net/zh-hant/aspose.slides/audioframe/rewind_audio/) | 確定音訊在播放完畢後是否自動倒回起始。<br/>            讀寫 **bool**。 |
| [`embedded`](/slides/python-net/zh-hant/aspose.slides/audioframe/embedded/) | 確定聲音是否嵌入簡報。<br/>            唯讀 **bool**。 |
| [`link_path_long`](/slides/python-net/zh-hant/aspose.slides/audioframe/link_path_long/) | 傳回或設定連結至 AudioFrame 的音訊檔案名稱。<br/>            讀寫 **str**。 |
| [`embedded_audio`](/slides/python-net/zh-hant/aspose.slides/audioframe/embedded_audio/) | 傳回或設定嵌入的音訊物件。<br/>            讀寫 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)。 |
| [`fade_in_duration`](/slides/python-net/zh-hant/aspose.slides/audioframe/fade_in_duration/) | 指定媒體初始淡入的時間長度（毫秒）。<br/>            讀寫 **float**。 |
| [`fade_out_duration`](/slides/python-net/zh-hant/aspose.slides/audioframe/fade_out_duration/) | 指定媒體結束淡出的時間長度（毫秒）。<br/>            讀寫 **float**。 |
| [`volume_value`](/slides/python-net/zh-hant/aspose.slides/audioframe/volume_value/) | 傳回或設定音訊音量（百分比）。<br/>            讀寫 **float**。 |
| [`trim_from_start`](/slides/python-net/zh-hant/aspose.slides/audioframe/trim_from_start/) | 指定播放期間從媒體開頭移除的時間長度（毫秒）。<br/>            讀寫 **float**。 |
| [`trim_from_end`](/slides/python-net/zh-hant/aspose.slides/audioframe/trim_from_end/) | 指定播放期間從媒體結尾移除的時間長度（毫秒）。<br/>            讀寫 **float**。 |
| [`caption_tracks`](/slides/python-net/zh-hant/aspose.slides/audioframe/caption_tracks/) | 取得與音訊框相關的閉路字幕集合。<br/>            此屬性為唯讀，回傳包含所有字幕軌道的 [`ICaptionsCollection`](/slides/python-net/zh-hant/aspose.slides/icaptionscollection)。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/audioframe/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖範圍類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/audioframe/write_as_svg/#iorawiobase) | 將形狀內容保存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容保存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/audioframe/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/audioframe/add_placeholder/#iplaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/audioframe/get_base_placeholder/#) | 傳回基本佔位符形狀（從版面配置或母片中繼承而來的形狀）。<br/>            若目前形狀未繼承則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/audioframe/get_visual_bounds/#) | 取得根據渲染內容計算出的形狀視覺範圍。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/audioframe/get_geometry_paths/#) | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | 使用 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。<br/>            將形狀的類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | 使用 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。<br/>            將形狀的類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/audioframe/create_shape_elements/#) | 建立並傳回形狀元素的陣列。 |

### 另請參閱
* 類別 [`AudioFrame`](/slides/python-net/zh-hant/aspose.slides/audioframe)
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)