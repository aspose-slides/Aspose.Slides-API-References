---
title: LegacyDiagram class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/legacydiagram/
---
## LegacyDiagram 類別

表示遺留圖示物件。

**繼承:**[`LegacyDiagram`](/slides/python-net/zh-hant/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

LegacyDiagram 類別公開以下成員：

## 屬性

| Property | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/is_text_holder/) | 判斷此圖形是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/placeholder/) | 取得圖形的預留位元。若圖形沒有預留位元則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/custom_data/) | 取得圖形的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/raw_frame/) | 取得或設定原始圖形框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/frame/) | 取得或設定圖形框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/line_format/) | 取得包含圖形線條格式屬性的 LineFormat 物件。<br/>            註：對於沒有線條屬性的某些圖形類型可能會傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/three_d_format/) | 取得圖形的 ThreeDFormat 物件以取得 3D 效果屬性。<br/>            註：對於沒有 3D 屬性的某些圖形類型可能會傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/effect_format/) | 取得包含套用於圖形的像素效果的 EffectFormat 物件。<br/>            註：對於沒有效果屬性的某些圖形類型可能會傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/fill_format/) | 取得包含圖形填充格式屬性的 FillFormat 物件。<br/>            註：對於沒有填充屬性的某些圖形類型可能會傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/hyperlink_click/) | 取得或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/hyperlink_mouse_over/) | 取得或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/hyperlink_manager/) | 取得超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/hidden/) | 判斷此圖形是否被隱藏。<br/>            可讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/z_order_position/) | 取得圖形在 Z 軸排序中的位置。<br/>            Shapes[0] 代表位於 Z 軸排序最底部的圖形，<br/>            Shapes[Shapes.Count - 1] 代表位於 Z 軸排序最前端的圖形。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/connection_site_count/) | 取得圖形的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/rotation/) | 取得或設定指定圖形繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/x/) | 取得或設定圖形左上角的 X 座標（以點為單位）。<br/>            可讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/y/) | 取得或設定圖形左上角的 Y 座標（以點為單位）。<br/>            可讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/width/) | 取得或設定圖形的寬度（以點為單位）。<br/>            可讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/height/) | 取得或設定圖形的高度（以點為單位）。<br/>            可讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/black_white_mode/) | 此屬性指定圖形在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/unique_id/) | 取得供外掛或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能會被使用者或程式重新指派，故不應視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/office_interop_shape_id/) | 取得在投影片範圍內唯一且在圖形生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式碼能可靠地從文件任何位置參照此圖形。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/alternative_text/) | 取得或設定與圖形相關的替代文字。<br/>            可讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/alternative_text_title/) | 取得或設定與圖形相關的替代文字標題。<br/>            可讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/name/) | 取得或設定圖形的名稱。<br/>            必須非 None。如有需要可使用空字串。<br/>            可讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/is_decorative/) | 取得或設定「標示為裝飾」選項<br/>            可讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/shape_lock/) | 取得圖形的鎖定資訊。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/is_grouped/) | 判斷此圖形是否為群組的一部份。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/parent_group/) | 若圖形為群組成員則傳回其父 GroupShape 物件，否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/slide/) | 取得圖形所在的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/presentation/) | 取得投影片所在的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/graphical_object_lock/) | 取得圖形的鎖定資訊。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |

## 方法

| Method | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/get_image/#) | 取得圖形縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 圖形縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | 取得圖形縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | 將圖形內容另存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將圖形內容另存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/remove_placeholder/#) | 定義此圖形不是預留位元。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | 若不存在則新增預留位元，並將預留位元屬性設定為指定的值。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/get_base_placeholder/#) | 取得基本的預留位元圖形（來自版面配置或母投影片，且目前圖形繼承自該圖形）。<br/>            若目前圖形未繼承則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/get_visual_bounds/#) | 取得根據圖形已呈現內容計算出的視覺邊界。 |
| [`convert_to_smart_art(self)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/convert_to_smart_art/#) | 將遺留圖示轉換為可編輯的 SmartArt 物件。<br/>            建立的 SmartArt 物件會以相同位置加入父群組圖形。 |
| [`convert_to_group_shape(self)`](/slides/python-net/zh-hant/aspose.slides/legacydiagram/convert_to_group_shape/#) | 將遺留圖示轉換為可編輯的群組圖形。<br/>            建立的 GroupShape 物件會以相同位置加入父群組圖形。 |


### 參見
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`LegacyDiagram`](/slides/python-net/zh-hant/aspose.slides/legacydiagram)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)