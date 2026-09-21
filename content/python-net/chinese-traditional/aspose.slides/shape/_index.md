---
title: Shape class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shape/
---
## Shape 類別

表示投影片上的形狀。

Shape 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/shape/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>        唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/shape/placeholder/) | 返回形狀的佔位符。如果形狀沒有佔位符，返回 None。<br/>        唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/shape/custom_data/) | 返回形狀的自訂資料。<br/>        唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/shape/raw_frame/) | 返回或設定原始形狀框架的屬性。<br/>        可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/shape/frame/) | 返回或設定形狀框架的屬性。<br/>        可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/shape/line_format/) | 返回包含形狀線條格式屬性的 LineFormat 物件。<br/>        注意：對於某些沒有線條屬性的形狀，可能返回 None。<br/>        唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/shape/three_d_format/) | 返回形狀的 ThreeDFormat 物件，包含 3D 效果屬性。<br/>        注意：對於某些沒有 3D 屬性的形狀，可能返回 None。<br/>        唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/shape/effect_format/) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>        注意：對於某些沒有效果屬性的形狀，可能返回 None。<br/>        唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/shape/fill_format/) | 返回包含形狀填充格式屬性的 FillFormat 物件。<br/>        注意：對於某些沒有填充屬性的形狀，可能返回 None。<br/>        唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/shape/hyperlink_click/) | 返回或設定滑鼠點擊時的超連結。<br/>        可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/shape/hyperlink_mouse_over/) | 返回或設定滑鼠懸停時的超連結。<br/>        可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/shape/hyperlink_manager/) | 返回超連結管理員。<br/>        唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/shape/hidden/) | 判斷形狀是否隱藏。<br/>        可讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/shape/z_order_position/) | 返回形狀在 Z 軸順序中的位置。<br/>        Shapes[0] 返回 Z 軸順序最背面的形狀，<br/>        而 Shapes[Shapes.Count - 1] 返回 Z 軸順序最前面的形狀。<br/>        唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/shape/connection_site_count/) | 返回形狀的連接點數量。<br/>        唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/shape/rotation/) | 返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>        可讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/shape/x/) | 取得或設定形狀左上角的 X 座標（以點為單位）。<br/>        可讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/shape/y/) | 取得或設定形狀左上角的 Y 座標（以點為單位）。<br/>        可讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/shape/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>        可讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/shape/height/) | 取得或設定形狀的高度（以點為單位）。<br/>        可讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/shape/black_white_mode/) | 此屬性指定形狀在黑白顯示模式下的呈現方式。<br/>        可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id/) | 返回一個內部、僅限於簡報範圍的識別碼，供外掛程式或其他程式碼使用。<br/>        由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。<br/>        唯讀 **int**。<br/>        另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id/) | 返回一個僅限於投影片範圍的唯一識別碼，在形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地在文件任何位置引用該形狀。<br/>        唯讀 **int**。<br/>        另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/shape/alternative_text/) | 返回或設定與形狀相關的替代文字。<br/>        可讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/shape/alternative_text_title/) | 返回或設定與形狀相關的替代文字標題。<br/>        可讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/shape/name/) | 返回或設定形狀的名稱。<br/>        必須非 None。如有需要可使用空字串。<br/>        可讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/shape/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>        可讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/shape/shape_lock/) | 返回形狀的鎖定資訊。<br/>        唯讀 [`IBaseShapeLock`](/slides/python-net/zh-hant/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/shape/is_grouped/) | 判斷形狀是否已群組。<br/>        唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/shape/parent_group/) | 如果形狀已群組，返回其父層 GroupShape 物件；否則返回 None。<br/>        唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/shape/slide/) | 返回形狀的父投影片。<br/>        唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/shape/presentation/) | 返回投影片的父簡報。<br/>        唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/shape/get_image/#) | 返回形狀縮圖。<br/>        預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | 返回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/shape/write_as_svg/#iorawiobase) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/shape/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/shape/add_placeholder/#iplaceholder) | 如果沒有佔位符，加入新的佔位符並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/shape/get_base_placeholder/#) | 返回基本的佔位符形狀（從版面配置或母片投影片繼承而來的形狀）。<br/>        如果當前形狀未繼承，則返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/shape/get_visual_bounds/#) | 取得根據渲染內容計算出的形狀視覺邊界。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)