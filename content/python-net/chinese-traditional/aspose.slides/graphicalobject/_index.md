---
title: GraphicalObject class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/graphicalobject/
---
## GraphicalObject 類別

表示抽象圖形物件。

**繼承:**[`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

GraphicalObject 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT.<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/placeholder/) | 返回形狀的占位符。如果形狀沒有占位符，則返回 None.<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/custom_data/) | 返回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/raw_frame/) | 返回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/frame/) | 返回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/line_format/) | 返回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註: 某些沒有線條屬性的形狀類型可能返回 None.<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/three_d_format/) | 返回形狀的 3D 效果屬性的 ThreeDFormat 物件。<br/>            註: 某些沒有 3D 屬性的形狀類型可能返回 None.<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/effect_format/) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            註: 某些沒有效果屬性的形狀類型可能返回 None.<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/fill_format/) | 返回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註: 某些沒有填充屬性的形狀類型可能返回 None.<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/hyperlink_click/) | 返回或設定滑鼠點擊時定義的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/hyperlink_mouse_over/) | 返回或設定滑鼠懸停時定義的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/hyperlink_manager/) | 返回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/hidden/) | 判斷形狀是否被隱藏。<br/>            讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/z_order_position/) | 返回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 返回位於 Z 軸順序最底部的形狀，<br/>            而 Shapes[Shapes.Count - 1] 返回位於 Z 軸順序最前端的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/connection_site_count/) | 返回形狀上的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/rotation/) | 返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/x/) | 取得或設定形狀左上角的 X 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/y/) | 取得或設定形狀左上角的 Y 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/unique_id/) | 返回供外掛或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**.<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/office_interop_shape_id/) | 返回在投影片範圍內唯一的識別碼，此識別碼在形狀生命週期內保持不變，且允許 PowerPoint 或互操作程式碼從文件中的任何位置可靠地參考該形狀。<br/>            唯讀 **int**.<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/alternative_text/) | 返回或設定與形狀相關聯的替代文字。<br/>            讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/alternative_text_title/) | 返回或設定與形狀相關聯的替代文字標題。<br/>            讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/name/) | 返回或設定形狀的名稱。<br/>            必須不為 None。如有需要請使用空字串。<br/>            讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/shape_lock/) | 返回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/is_grouped/) | 判斷形狀是否已群組。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/parent_group/) | 如果形狀已群組，返回父層 GroupShape 物件。否則返回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/slide/) | 返回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/presentation/) | 返回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/graphical_object_lock/) | 返回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/get_image/#) | 返回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | 返回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/remove_placeholder/#) | 定義此形狀不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | 如果沒有占位符，則新增一個占位符並將占位符屬性設定為指定的。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/get_base_placeholder/#) | 返回基本占位符形狀（來自佈局和/或母片，且當前形狀繼承自該形狀的形狀）。<br/>            如果當前形狀未繼承，則返回 None. |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/graphicalobject/get_visual_bounds/#) | 取得根據渲染內容計算出的形狀視覺邊界。 |

### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)