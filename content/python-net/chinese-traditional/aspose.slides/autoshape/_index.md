---
title: AutoShape class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/autoshape/
---
## AutoShape 類別

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/zh-hant/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The AutoShape type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/autoshape/is_text_holder/) | 判斷此圖形是否為 TextHolder_PPT。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/autoshape/placeholder/) | 返回圖形的 placeholder。若圖形沒有 placeholder，則返回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/autoshape/custom_data/) | 返回圖形的 custom data。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/autoshape/raw_frame/) | 返回或設定原始 shape frame 的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/autoshape/frame/) | 返回或設定 shape frame 的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/autoshape/line_format/) | 返回包含圖形線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的圖形可能返回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/autoshape/three_d_format/) | 返回包含圖形 3D 效果屬性的 ThreeDFormat 物件。<br/>            註：對於某些沒有 3D 屬性的圖形可能返回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/autoshape/effect_format/) | 返回包含套用於圖形的像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的圖形可能返回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/autoshape/fill_format/) | 返回包含圖形填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的圖形可能返回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/autoshape/hyperlink_click/) | 返回或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/autoshape/hyperlink_mouse_over/) | 返回或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/autoshape/hyperlink_manager/) | 返回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/autoshape/hidden/) | 判斷此圖形是否為隱藏。<br/>            可讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/autoshape/z_order_position/) | 返回圖形在 z 順序中的位置。<br/>            Shapes[0] 返迴 z 順序最底的圖形，<br/>            Shapes[Shapes.Count - 1] 返迴 z 順序最前的圖形。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/autoshape/connection_site_count/) | 返回圖形的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/autoshape/rotation/) | 返回或設定圖形繞 z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/autoshape/x/) | 取得或設定圖形左上角的 x 坐標（以點為單位）。<br/>            可讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/autoshape/y/) | 取得或設定圖形左上角的 y 坐標（以點為單位）。<br/>            可讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/autoshape/width/) | 取得或設定圖形的寬度（以點為單位）。<br/>            可讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/autoshape/height/) | 取得或設定圖形的高度（以點為單位）。<br/>            可讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/autoshape/black_white_mode/) | 屬性指定圖形在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/autoshape/unique_id/) | 返回供外掛程式或其他程式使用的內部簡報範圍識別碼。<br/>            因此值可能會被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**.<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/autoshape/office_interop_shape_id/) | 返回在簡報生命週期內保持不變的投影片範圍唯一識別碼，可讓 PowerPoint 或 interop 程式碼在文件任意位置可靠參照圖形。<br/>            唯讀 **int**.<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/autoshape/alternative_text/) | 返回或設定圖形的替代文字。<br/>            可讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/autoshape/alternative_text_title/) | 返回或設定圖形替代文字的標題。<br/>            可讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/autoshape/name/) | 返回或設定圖形的名稱。<br/>            必須非 None。如需可使用空字串。<br/>            可讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/autoshape/is_decorative/) | 取得或設定「標記為裝飾」選項。<br/>            可讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/autoshape/shape_lock/) | 返回圖形的鎖定設定。<br/>            唯讀 [`IAutoShapeLock`](/slides/python-net/zh-hant/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/autoshape/is_grouped/) | 判斷此圖形是否為群組的一部分。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/autoshape/parent_group/) | 若圖形屬於群組，返回其父 GroupShape 物件；否則返回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/autoshape/slide/) | 返回圖形所在的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/autoshape/presentation/) | 返回投影片所在的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/autoshape/shape_style/) | 返回圖形的樣式物件。<br/>            唯讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/autoshape/shape_type/) | 返回或設定幾何預設類型。<br/>            註：變更值時所有調整值將重置為預設值。<br/>            可讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/autoshape/adjustments/) | 返回圖形的調整值集合。<br/>            唯讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/zh-hant/aspose.slides/autoshape/auto_shape_lock/) | 返回自動圖形的鎖定設定。<br/>            唯讀 [`IAutoShapeLock`](/slides/python-net/zh-hant/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/zh-hant/aspose.slides/autoshape/text_frame/) | 返回 AutoShape 的 TextFrame 物件。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/zh-hant/aspose.slides/autoshape/use_background_fill/) | 判斷此自動圖形是否應使用投影片的背景填充，而非樣式或填充格式指定的填充。<br/>            可讀寫 **bool**. |
| [`is_text_box`](/slides/python-net/zh-hant/aspose.slides/autoshape/is_text_box/) | 指定此圖形是否為文字方塊。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/autoshape/get_image/#) | 返回圖形縮圖。<br/>            ShapeThumbnailBounds.Shape 圖形縮圖邊界類型預設使用。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | 返回圖形縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/autoshape/write_as_svg/#iorawiobase) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/autoshape/remove_placeholder/#) | 定義此圖形不是 placeholder。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/autoshape/add_placeholder/#iplaceholder) | 若無 placeholder，則新增一個，並將 placeholder 屬性設定為指定的。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/autoshape/get_base_placeholder/#) | 返回基本的 placeholder 圖形（從佈局或母投影片繼承的圖形）。<br/>            若當前圖形未繼承則回傳 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/autoshape/get_visual_bounds/#) | 取得依據渲染內容計算的圖形視覺邊界。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/autoshape/get_geometry_paths/#) | 返回幾何圖形路徑的副本。座標相對於圖形左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | 依據 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新圖形幾何。座標必須相對於圖形左上角。<br/>             將圖形類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | 依據 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新圖形幾何。座標必須相對於圖形左上角。<br/>             將圖形類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/autoshape/create_shape_elements/#) | 建立並返回圖形元素的陣列。 |
| [`add_text_frame(self, text)`](/slides/python-net/zh-hant/aspose.slides/autoshape/add_text_frame/#str) | 為圖形新增 TextFrame。<br/>            若圖形已具備 TextFrame，則直接變更其文字。 |

### 另請參閱
* 類別 [`AutoShape`](/slides/python-net/zh-hant/aspose.slides/autoshape)
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)