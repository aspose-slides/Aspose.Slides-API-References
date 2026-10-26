---
title: ZoomObject class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/zoomobject/
---
## ZoomObject 類別

Represents an Zoom object in a slide.

**Inheritance:**[`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The ZoomObject type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/zoomobject/is_text_holder/) | 確定此形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/zoomobject/placeholder/) | 傳回形狀的預留位置。若形狀沒有預留位置則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/zoomobject/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/zoomobject/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/zoomobject/frame/) | 傳回或設定形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/zoomobject/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀類型，可能會傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/zoomobject/three_d_format/) | 傳回包含形狀 3D 效果屬性的 ThreeDFormat 物件。<br/>            註：對於某些沒有 3D 屬性的形狀類型，可能會傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/zoomobject/effect_format/) | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀類型，可能會傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/zoomobject/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀類型，可能會傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/zoomobject/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/zoomobject/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/zoomobject/hyperlink_manager/) | 傳回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/zoomobject/hidden/) | 確定此形狀是否被隱藏。<br/>            可讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/zoomobject/z_order_position/) | 傳回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 傳回 Z 軸順序最背後的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回 Z 軸順序最前面的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/zoomobject/connection_site_count/) | 傳回形狀的連接點數目。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/zoomobject/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度）。<br/>            正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/zoomobject/x/) | 取得或設定形狀左上角的 x 座標（以點為單位）。<br/>            可讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/zoomobject/y/) | 取得或設定形狀左上角的 y 座標（以點為單位）。<br/>            可讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/zoomobject/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            可讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/zoomobject/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            可讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/zoomobject/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/zoomobject/unique_id/) | 傳回用於外掛程式或其他程式碼的內部、簡報範圍辨識碼。<br/>            由於此值可被使用者或程式重新指派，不能視為持續的唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/zoomobject/office_interop_shape_id/) | 傳回在投影片範圍內唯一且在形狀存續期間保持不變的辨識碼，<br/>            讓 PowerPoint 或互通程式碼能從文件的任何位置可靠地參考該形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/zoomobject/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            可讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/zoomobject/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            可讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/zoomobject/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。如有需要，請使用空字串。<br/>            可讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/zoomobject/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            可讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/zoomobject/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/zoomobject/is_grouped/) | 確定此形狀是否已分組。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/zoomobject/parent_group/) | 若形狀已分組則傳回其父級 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/zoomobject/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/zoomobject/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/zoomobject/graphical_object_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/zh-hant/aspose.slides/zoomobject/image_type/) | 取得或設定 Zoom 物件的影像類型。<br/>            可讀寫 [`ZoomImageType`](/slides/python-net/zh-hant/aspose.slides/zoomimagetype)。<br/>            預設值：Preview |
| [`return_to_parent`](/slides/python-net/zh-hant/aspose.slides/zoomobject/return_to_parent/) | 取得或設定投影片播放時的導覽行為。<br/>            可讀寫 **bool**。<br/>            預設值：false |
| [`show_background`](/slides/python-net/zh-hant/aspose.slides/zoomobject/show_background/) | 取得或設定指定 Zoom 是否使用目標投影片背景的值。<br/>            可讀寫 **bool**。<br/>            預設值：true |
| [`zoom_image`](/slides/python-net/zh-hant/aspose.slides/zoomobject/zoom_image/) | 取得或設定 Zoom 物件的影像。<br/>            可讀寫 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/zh-hant/aspose.slides/zoomobject/transition_duration/) | 取得或設定 Zoom 與投影片之間轉場的持續時間。<br/>            可讀寫 **float**。<br/>            預設值：1.0f |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/remove_placeholder/#) | 定義此形狀不是預留位置。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | 若不存在則新增預留位置，並將預留位置屬性設定為指定的。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/get_base_placeholder/#) | 傳回基本的預留位置形狀（來自版面配置和/或母片，且當前形狀繼承自該形狀）。<br/>            若當前形狀未繼承則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/zoomobject/get_visual_bounds/#) | 取得依其渲染內容計算出的形狀可視邊界。 |

### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)