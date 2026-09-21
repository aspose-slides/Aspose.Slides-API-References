---
title: Table class
second_title: Aspose.Slides 的 Python .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/table/
---
## Table 類別

表示投影片上的表格。

**繼承:**[`Table`](/slides/python-net/zh-hant/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

Table 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/table/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/table/placeholder/) | 傳回形狀的佔位元件。如果形狀沒有佔位元件，傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/table/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/table/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/table/frame/) | 傳回或設定形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/table/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            注意：對於某些沒有線條屬性的形狀，可能傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/table/three_d_format/) | 傳回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。<br/>            注意：對於某些沒有 3D 屬性的形狀，可能傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/table/effect_format/) | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            注意：對於某些沒有效果屬性的形狀，可能傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/table/fill_format/) | 傳回包含 Table 填充格式的 TableFormat.FillFormat 物件。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/table/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/table/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/table/hyperlink_manager/) | 傳回超連結管理員。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/table/hidden/) | 判斷形狀是否為隱藏。<br/>            可讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/table/z_order_position/) | 傳回形狀在 Z 軸排序中的位置。<br/>            Shapes[0] 傳回 Z 軸排序最靠後的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回 Z 軸排序最前面的形狀。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/table/connection_site_count/) | 傳回形狀的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/table/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的度數。<br/>            正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/table/x/) | 取得或設定形狀左上角的 X 座標，單位為點 (points)。<br/>            可讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/table/y/) | 取得或設定形狀左上角的 Y 座標，單位為點 (points)。<br/>            可讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/table/width/) | 取得或設定形狀的寬度，單位為點 (points)。<br/>            可讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/table/height/) | 取得或設定形狀的高度，單位為點 (points)。<br/>            可讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/table/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/table/unique_id/) | 傳回一個內部、以投影片範圍為基礎的辨識碼，供外掛程式或其他程式碼使用。<br/>            由於此值可能被使用者或程式重新指派，不能視為永久唯一的鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/table/office_interop_shape_id/) | 傳回一個以投影片為範圍的唯一辨識碼，在形狀的生命週期內保持不變，且可讓 PowerPoint 或互通程式碼自文件任何位置可靠地參照此形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/table/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            可讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/table/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            可讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/table/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。如有需要可使用空字串。<br/>            可讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/table/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            可讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/table/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/table/is_grouped/) | 判斷形狀是否已分組。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/table/parent_group/) | 如果形狀已分組，傳回父 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/table/slide/) | 傳回形狀所在的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/table/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/table/graphical_object_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`rows`](/slides/python-net/zh-hant/aspose.slides/table/rows/) | 傳回列的集合。<br/>            唯讀 [`IRowCollection`](/slides/python-net/zh-hant/aspose.slides/irowcollection)。 |
| [`columns`](/slides/python-net/zh-hant/aspose.slides/table/columns/) | 傳回欄的集合。<br/>            唯讀 [`IColumnCollection`](/slides/python-net/zh-hant/aspose.slides/icolumncollection)。 |
| [`table_format`](/slides/python-net/zh-hant/aspose.slides/table/table_format/) | 傳回包含此表格格式屬性的 TableFormat 物件。<br/>            唯讀 [`ITableFormat`](/slides/python-net/zh-hant/aspose.slides/itableformat)。 |
| [`style_preset`](/slides/python-net/zh-hant/aspose.slides/table/style_preset/) | 取得或設定內建表格樣式。<br/>            可讀寫 [`TableStylePreset`](/slides/python-net/zh-hant/aspose.slides/tablestylepreset)。 |
| [`right_to_left`](/slides/python-net/zh-hant/aspose.slides/table/right_to_left/) | 判斷表格是否採用從右至左的閱讀順序。<br/>            可讀寫 **bool**。 |
| [`first_row`](/slides/python-net/zh-hant/aspose.slides/table/first_row/) | 判斷表格的第一列是否必須以特殊格式繪製。<br/>            可讀寫 **bool**。 |
| [`first_col`](/slides/python-net/zh-hant/aspose.slides/table/first_col/) | 判斷表格的第一欄是否必須以特殊格式繪製。<br/>            可讀寫 **bool**。 |
| [`last_row`](/slides/python-net/zh-hant/aspose.slides/table/last_row/) | 判斷表格的最後一列是否必須以特殊格式繪製。<br/>            可讀寫 **bool**。 |
| [`last_col`](/slides/python-net/zh-hant/aspose.slides/table/last_col/) | 判斷表格的最後一欄是否必須以特殊格式繪製。<br/>            可讀寫 **bool**。 |
| [`horizontal_banding`](/slides/python-net/zh-hant/aspose.slides/table/horizontal_banding/) | 判斷偶數列是否必須以不同的格式繪製。<br/>            可讀寫 **bool**。 |
| [`vertical_banding`](/slides/python-net/zh-hant/aspose.slides/table/vertical_banding/) | 判斷偶數欄是否必須以不同的格式繪製。<br/>            可讀寫 **bool**。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/table/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/table/write_as_svg/#iorawiobase) | 將 Shape 的內容另存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 的內容另存為 SVG 檔案。 |
| [`set_text_format(self, source)`](/slides/python-net/zh-hant/aspose.slides/table/set_text_format/#iportionformat) | 將已定義的部分格式屬性套用至所有表格儲存格的部分。 |
| [`set_text_format(self, source)`](/slides/python-net/zh-hant/aspose.slides/table/set_text_format/#iparagraphformat) | 將已定義的段落格式屬性套用至所有表格儲存格的段落。 |
| [`set_text_format(self, source)`](/slides/python-net/zh-hant/aspose.slides/table/set_text_format/#itextframeformat) | 將已定義的文字框格式屬性套用至所有表格儲存格的文字框。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/table/remove_placeholder/#) | 定義此形狀不是佔位元件。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/table/add_placeholder/#iplaceholder) | 如果不存在佔位元件，則新增一個佔位元件，並將佔位元件屬性設定為指定的佔位元件。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/table/get_base_placeholder/#) | 傳回基本的佔位元件形狀（即當前形狀繼承自的版面配置或母片投影片中的形狀）。<br/>            若當前形狀未繼承，則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/table/get_visual_bounds/#) | 取得形狀根據渲染內容計算出的視覺邊界。 |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/zh-hant/aspose.slides/table/merge_cells/#icell-icell-bool) | 合併相鄰的儲存格。 |

### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`Table`](/slides/python-net/zh-hant/aspose.slides/table)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)