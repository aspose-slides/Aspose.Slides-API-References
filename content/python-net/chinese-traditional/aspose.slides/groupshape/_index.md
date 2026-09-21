---
title: GroupShape class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/groupshape/
---
## GroupShape 類別

表示投影片上形狀的群組。

**繼承:**[`GroupShape`](/slides/python-net/zh-hant/aspose.slides/groupshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

GroupShape 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/groupshape/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/groupshape/placeholder/) | 傳回形狀的佔位符。如果形狀沒有佔位符，則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/groupshape/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/groupshape/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/groupshape/frame/) | 傳回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/groupshape/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            注意：對於 GroupShape 物件會傳回 None，因為它們沒有線條屬性。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/groupshape/three_d_format/) | 傳回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。<br/>            注意：對於某些沒有 3D 屬性的形狀，可能會傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/groupshape/effect_format/) | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            注意：對於某些沒有效果屬性的形狀，可能會傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/groupshape/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            注意：對於某些沒有填充屬性的形狀，可能會傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/groupshape/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/groupshape/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/groupshape/hyperlink_manager/) | 傳回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/groupshape/hidden/) | 判斷形狀是否隱藏。<br/>            讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/groupshape/z_order_position/) | 傳回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 傳回 Z 軸順序最背面的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回最前面的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/groupshape/connection_site_count/) | 傳回形狀的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/groupshape/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/groupshape/x/) | 取得或設定形狀左上角的 X 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/groupshape/y/) | 取得或設定形狀左上角的 Y 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/groupshape/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/groupshape/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/groupshape/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/groupshape/unique_id/) | 傳回供外掛或其他程式使用的內部、簡報範圍識別碼。<br/>            由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參考 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/groupshape/office_interop_shape_id/) | 傳回在投影片範圍內唯一的識別碼，於形狀的整個生命週期保持不變，讓 PowerPoint 或 interop 程式碼能從文件任何位置可靠地引用此形狀。<br/>            唯讀 **int**。<br/>            另請參考 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/groupshape/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/groupshape/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/groupshape/name/) | 傳回或設定形狀的名稱。<br/>            必須不是 None。如有需要可使用空字串。<br/>            讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/groupshape/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/groupshape/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGroupShapeLock`](/slides/python-net/zh-hant/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/groupshape/is_grouped/) | 判斷形狀是否已群組。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/groupshape/parent_group/) | 如果形狀已群組，傳回其父 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/groupshape/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/groupshape/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/zh-hant/aspose.slides/groupshape/group_shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGroupShapeLock`](/slides/python-net/zh-hant/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/groupshape/shapes/) | 傳回群組內的形狀集合。<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/groupshape/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖. |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/groupshape/write_as_svg/#iorawiobase) | 將形狀內容儲存為 SVG 檔案. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容儲存為 SVG 檔案. |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/groupshape/remove_placeholder/#) | 定義此形狀不是佔位符. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/groupshape/add_placeholder/#iplaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符. |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/groupshape/get_base_placeholder/#) | 傳回基本佔位符形狀（來自版面配置和/或母片，為當前形狀所繼承的形狀）。<br/>            若當前形狀未繼承，則傳回 None. |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/groupshape/get_visual_bounds/#) | 取得根據形狀渲染內容計算出的視覺邊界. |

### 另見
* 類別 [`GroupShape`](/slides/python-net/zh-hant/aspose.slides/groupshape)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)