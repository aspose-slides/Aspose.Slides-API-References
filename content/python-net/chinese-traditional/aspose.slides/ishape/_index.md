---
title: IShape class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishape/
---
## IShape 類別

代表投影片上的形狀。

IShape 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/ishape/is_text_holder/) | 判定形狀是否為 TextHolder。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/ishape/placeholder/) | 傳回形狀的佔位符。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/ishape/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/ishape/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/ishape/frame/) | 傳回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/ishape/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/ishape/three_d_format/) | 傳回包含形狀線條格式屬性的 ThreeDFormat 物件。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/ishape/effect_format/) | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/ishape/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/ishape/hidden/) | 判定形狀是否隱藏。<br/>            讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/ishape/z_order_position/) | 傳回形狀在 Z 序中的位置。<br/>            Shapes[0] 傳回 Z 序最後方的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回 Z 序最前方的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/ishape/connection_site_count/) | 傳回形狀上的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/ishape/rotation/) | 傳回或設定指定形狀繞 z 軸旋轉的度數。<br/>            正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/ishape/x/) | 取得或設定形狀左上角的 x 坐標（以點為單位）。<br/>            讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/ishape/y/) | 取得或設定形狀左上角的 y 坐標（以點為單位）。<br/>            讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/ishape/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/ishape/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**. |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/ishape/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/ishape/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/ishape/name/) | 傳回或設定形狀的名稱。<br/>            讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/ishape/is_decorative/) | 取得或設定「標記為裝飾性」選項<br/>            讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/ishape/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IBaseShapeLock`](/slides/python-net/zh-hant/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/ishape/unique_id/) | 傳回供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能由使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`IShape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/ishape/office_interop_shape_id/) | 傳回在投影片範圍內唯一且在形狀整個生命週期內保持不變的識別碼，讓 PowerPoint 或互通程式碼能從文件任何位置可靠地參照該形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`IShape.unique_id`](/slides/python-net/zh-hant/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/ishape/is_grouped/) | 判定形狀是否已群組。<br/>            唯讀 **bool**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/ishape/black_white_mode/) | 此屬性指定形狀在黑白顯示模式下的渲染方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/ishape/parent_group/) | 若形狀已群組，傳回其父層 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/ishape/hyperlink_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/ishape/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/ishape/write_as_svg/#iorawiobase) | 將形狀內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容儲存為 SVG 檔案。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/ishape/add_placeholder/#iplaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/ishape/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/ishape/get_base_placeholder/#) | 傳回基本佔位符形狀（來自版面配置及/或母片，且目前形狀繼承自該形狀）。<br/>            若目前形狀未繼承，則傳回 None。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)