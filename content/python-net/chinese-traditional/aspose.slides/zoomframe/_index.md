---
title: ZoomFrame class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/zoomframe/
---
## ZoomFrame 類別

Represents a Slide Zoom object in a slide.

**Inheritance:**[`ZoomFrame`](/slides/python-net/zh-hant/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The ZoomFrame type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/zoomframe/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/zoomframe/placeholder/) | 傳回形狀的佔位符。如果形狀沒有佔位符，則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/zoomframe/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/zoomframe/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/zoomframe/frame/) | 傳回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/zoomframe/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/zoomframe/three_d_format/) | 傳回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。<br/>            註：對於某些沒有 3D 屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/zoomframe/effect_format/) | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/zoomframe/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/zoomframe/hyperlink_click/) | 傳回或設定滑鼠點擊時定義的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/zoomframe/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時定義的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/zoomframe/hyperlink_manager/) | 傳回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/zoomframe/hidden/) | 判斷形狀是否為隱藏。<br/>            讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/zoomframe/z_order_position/) | 傳回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 傳回 Z 軸順序最後面的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回 Z 軸順序最前面的形狀。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/zoomframe/connection_site_count/) | 傳回形狀的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/zoomframe/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。<br/>            正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/zoomframe/x/) | 取得或設定形狀左上角的 x 座標（以點為單位）。<br/>            讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/zoomframe/y/) | 取得或設定形狀左上角的 y 座標（以點為單位）。<br/>            讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/zoomframe/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/zoomframe/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/zoomframe/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的渲染方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/zoomframe/unique_id/) | 傳回內部的、以簡報為範圍的識別碼，供外掛或其他程式碼使用。<br/>            由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/zoomframe/office_interop_shape_id/) | 傳回以投影片為範圍的唯一識別碼，於形狀的生命週期內保持不變，<br/>            並讓 PowerPoint 或互通程式碼能在文件任意位置可靠地參照該形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/zoomframe/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/zoomframe/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/zoomframe/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。如有需要可使用空字串。<br/>            讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/zoomframe/is_decorative/) | 取得或設定「標示為裝飾」選項<br/>            讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/zoomframe/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/zoomframe/is_grouped/) | 判斷形狀是否為組合形狀。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/zoomframe/parent_group/) | 若形狀已組合，傳回其父層 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/zoomframe/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/zoomframe/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/zoomframe/graphical_object_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`image_type`](/slides/python-net/zh-hant/aspose.slides/zoomframe/image_type/) | 取得或設定 Zoom 物件的影像類型。<br/>            讀寫 [`ZoomImageType`](/slides/python-net/zh-hant/aspose.slides/zoomimagetype)。<br/>            預設值：Preview |
| [`return_to_parent`](/slides/python-net/zh-hant/aspose.slides/zoomframe/return_to_parent/) | 取得或設定投影片放映時的導覽行為。<br/>            讀寫 **bool**。<br/>            預設值：false |
| [`show_background`](/slides/python-net/zh-hant/aspose.slides/zoomframe/show_background/) | 取得或設定指定 Zoom 是否使用目的投影片背景的值。<br/>            讀寫 **bool**。<br/>            預設值：true |
| [`zoom_image`](/slides/python-net/zh-hant/aspose.slides/zoomframe/zoom_image/) | 取得或設定 Zoom 物件的影像。<br/>            讀寫 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |
| [`transition_duration`](/slides/python-net/zh-hant/aspose.slides/zoomframe/transition_duration/) | 取得或設定 Zoom 與投影片之間過渡的持續時間。<br/>            讀寫 **float**。<br/>            預設值：1.0f |
| [`target_slide`](/slides/python-net/zh-hant/aspose.slides/zoomframe/target_slide/) | 取得或設定 Slide Zoom 物件所連結的投影片物件。<br/>            讀寫 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | 如果不存在佔位符，則新增一個，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/get_base_placeholder/#) | 傳回一個基本的佔位符形狀（來自版面配置和/或母片，且當前形狀繼承自該形狀）。<br/>            若當前形狀未繼承，則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/zoomframe/get_visual_bounds/#) | 取得根據形狀已渲染內容計算出的視覺邊界。 |

### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`ZoomFrame`](/slides/python-net/zh-hant/aspose.slides/zoomframe)
* 類別 [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)