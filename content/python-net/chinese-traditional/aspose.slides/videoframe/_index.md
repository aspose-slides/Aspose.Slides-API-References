---
title: VideoFrame class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/videoframe/
---
## VideoFrame 類別

Represents a video clip on a slide.

**Inheritance:**[`VideoFrame`](/slides/python-net/zh-hant/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The VideoFrame type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/videoframe/is_text_holder/) | 確定此形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/videoframe/placeholder/) | 傳回形狀的佔位符。如果形狀沒有佔位符，則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/videoframe/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/videoframe/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/videoframe/frame/) | 傳回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/videoframe/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/videoframe/three_d_format/) | 傳回形狀的 ThreeDFormat 物件，提供 3D 效果屬性。<br/>            註：對於某些沒有 3D 屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/videoframe/effect_format/) | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/videoframe/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/videoframe/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/videoframe/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/videoframe/hyperlink_manager/) | 傳回超連結管理員。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/videoframe/hidden/) | 確定形狀是否隱藏。<br/>            讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/videoframe/z_order_position/) | 傳回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 傳回 Z 軸順序最背面的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回最前面的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/videoframe/connection_site_count/) | 傳回形狀的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/videoframe/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/videoframe/x/) | 取得或設定形狀左上角的 X 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/videoframe/y/) | 取得或設定形狀左上角的 Y 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/videoframe/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/videoframe/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/videoframe/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/videoframe/unique_id/) | 傳回供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能被使用者或程式重新指派，不能視為持久的唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/videoframe/office_interop_shape_id/) | 傳回在投影片範圍內唯一的識別碼，於形狀存續期間保持不變，讓 PowerPoint 或 interop 程式碼能可靠地在文件任意位置參照此形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/videoframe/alternative_text/) | 傳回或設定與形狀相關的替代文字。<br/>            讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/videoframe/alternative_text_title/) | 傳回或設定與形狀相關的替代文字標題。<br/>            讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/videoframe/name/) | 傳回或設定形狀的名稱。<br/>            不得為 None。如有需要請使用空字串。<br/>            讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/videoframe/is_decorative/) | 取得或設定「標示為裝飾」選項<br/>            讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/videoframe/shape_lock/) | 傳回形狀的鎖定狀態。<br/>            唯讀 [`IPictureFrameLock`](/slides/python-net/zh-hant/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/videoframe/is_grouped/) | 確定形狀是否已群組。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/videoframe/parent_group/) | 如果形狀已群組則傳回父層 GroupShape 物件，否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/videoframe/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/videoframe/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/videoframe/shape_style/) | 傳回形狀的樣式物件。<br/>            唯讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/videoframe/shape_type/) | 傳回或設定 PictureFrame 的 AutoShape 類型。<br/>            允許的項目皆屬於集合 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)，<br/>            除了各種線條：<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5。<br/><br/><br/>            讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/videoframe/adjustments/) | 傳回形狀的調整值集合。<br/>            唯讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/zh-hant/aspose.slides/videoframe/picture_frame_lock/) | 傳回形狀的鎖定狀態。<br/>            唯讀 [`IPictureFrameLock`](/slides/python-net/zh-hant/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/zh-hant/aspose.slides/videoframe/picture_format/) | 傳回圖片框架的 PictureFillFormat 物件。<br/>            唯讀 [`IPictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/zh-hant/aspose.slides/videoframe/relative_scale_height/) | 傳回或設定圖片框架高度的比例（相對於原始圖片大小），值 1.0 代表 100%。<br/>            讀寫 **float**. |
| [`relative_scale_width`](/slides/python-net/zh-hant/aspose.slides/videoframe/relative_scale_width/) | 傳回或設定圖片框架寬度的比例（相對於原始圖片大小），值 1.0 代表 100%。<br/>            讀寫 **float**. |
| [`is_cameo`](/slides/python-net/zh-hant/aspose.slides/videoframe/is_cameo/) | 確定 PictureFrame 是否為 Cameo 物件。<br/>            唯讀 **bool**. |
| [`rewind_video`](/slides/python-net/zh-hant/aspose.slides/videoframe/rewind_video/) | 確定影片在播放結束後是否自動倒回起始位置。<br/>            讀寫 **bool**. |
| [`play_loop_mode`](/slides/python-net/zh-hant/aspose.slides/videoframe/play_loop_mode/) | 確定影片是否循環播放。<br/>            讀寫 **bool**. |
| [`hide_at_showing`](/slides/python-net/zh-hant/aspose.slides/videoframe/hide_at_showing/) | 確定 VideoFrame 是否被隱藏。<br/>            讀寫 **bool**. |
| [`volume`](/slides/python-net/zh-hant/aspose.slides/videoframe/volume/) | 傳回或設定音訊音量。<br/>            讀寫 [`AudioVolumeMode`](/slides/python-net/zh-hant/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/zh-hant/aspose.slides/videoframe/play_mode/) | 傳回或設定影片播放模式。<br/>            讀寫 [`VideoPlayModePreset`](/slides/python-net/zh-hant/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/zh-hant/aspose.slides/videoframe/full_screen_mode/) | 確定影片是否以全螢幕模式顯示。<br/>            讀寫 **bool**. |
| [`link_path_long`](/slides/python-net/zh-hant/aspose.slides/videoframe/link_path_long/) | 傳回或設定與 VideoFrame 連結的影片檔案名稱。<br/>            讀寫 **str**. |
| [`embedded_video`](/slides/python-net/zh-hant/aspose.slides/videoframe/embedded_video/) | 傳回或設定內嵌影片物件。<br/>            讀寫 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/zh-hant/aspose.slides/videoframe/trim_from_start/) | 剪輯開始 [毫秒] |
| [`trim_from_end`](/slides/python-net/zh-hant/aspose.slides/videoframe/trim_from_end/) | 剪輯結束 [毫秒] |
| [`caption_tracks`](/slides/python-net/zh-hant/aspose.slides/videoframe/caption_tracks/) | 取得與影片框架相關的閉路字幕集合。<br/>             此屬性為唯讀，傳回包含所有字幕軌道的 [`ICaptionsCollection`](/slides/python-net/zh-hant/aspose.slides/icaptionscollection). |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/videoframe/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖界限類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/videoframe/write_as_svg/#iorawiobase) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/videoframe/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/videoframe/add_placeholder/#iplaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/videoframe/get_base_placeholder/#) | 傳回基本佔位符形狀（從版面配置或母片中繼承而來的形狀）。<br/>            若當前形狀未繼承，則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/videoframe/get_visual_bounds/#) | 取得根據已渲染內容計算的形狀視覺界限。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/videoframe/get_geometry_paths/#) | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。<br/>             將形狀類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 更改為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。<br/>             將形狀類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 更改為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/videoframe/create_shape_elements/#) | 建立並傳回形狀元素的陣列。 |

### 另請參閱
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`VideoFrame`](/slides/python-net/zh-hant/aspose.slides/videoframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)