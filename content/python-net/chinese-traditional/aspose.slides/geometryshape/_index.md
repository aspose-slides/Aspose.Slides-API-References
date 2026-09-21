---
title: GeometryShape class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/geometryshape/
---
## GeometryShape 類別

代表所有幾何形狀的父類別。

**繼承:**[`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

GeometryShape 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/geometryshape/is_text_holder/) | 判斷此形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/geometryshape/placeholder/) | 返回形狀的佔位符。如果形狀沒有佔位符，返回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/geometryshape/custom_data/) | 返回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/geometryshape/raw_frame/) | 取得或設定原始形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/geometryshape/frame/) | 取得或設定形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/geometryshape/line_format/) | 返回包含形狀線條格式屬性的 LineFormat 物件。<br/>            注意：對於某些沒有線條屬性的形狀，可能返回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/geometryshape/three_d_format/) | 返回形狀的 ThreeDFormat 物件，其包含 3D 效果屬性。<br/>            注意：對於某些沒有 3D 屬性的形狀，可能返回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/geometryshape/effect_format/) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            注意：對於某些沒有效果屬性的形狀，可能返回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/geometryshape/fill_format/) | 返回包含形狀填充格式屬性的 FillFormat 物件。<br/>            注意：對於某些沒有填充屬性的形狀，可能返回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/geometryshape/hyperlink_click/) | 取得或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/geometryshape/hyperlink_mouse_over/) | 取得或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/geometryshape/hyperlink_manager/) | 返回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/geometryshape/hidden/) | 判斷此形狀是否隱藏。<br/>            可讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/geometryshape/z_order_position/) | 返回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 返回位於 Z 軸最底層的形狀，<br/>            而 Shapes[Shapes.Count - 1] 返回位於 Z 軸最前端的形狀。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/geometryshape/connection_site_count/) | 返回形狀的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/geometryshape/rotation/) | 取得或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。<br/>            可讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/geometryshape/x/) | 取得或設定形狀左上角的 X 座標（以點為單位）。<br/>            可讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/geometryshape/y/) | 取得或設定形狀左上角的 Y 座標（以點為單位）。<br/>            可讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/geometryshape/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            可讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/geometryshape/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            可讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/geometryshape/black_white_mode/) | 此屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/geometryshape/unique_id/) | 返回供外掛或其他程式碼使用的內部、僅限於簡報範圍的識別碼。<br/>            因為此值可能被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/geometryshape/office_interop_shape_id/) | 返回一個在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，並允許 PowerPoint 或互操作程式碼在文件任意位置可靠地引用該形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/geometryshape/alternative_text/) | 取得或設定與形狀相關聯的替代文字。<br/>            可讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/geometryshape/alternative_text_title/) | 取得或設定與形狀相關聯的替代文字標題。<br/>            可讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/geometryshape/name/) | 取得或設定形狀的名稱。<br/>            必須不為 None。必要時可使用空字串。<br/>            可讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/geometryshape/is_decorative/) | 取得或設定「標記為裝飾」選項。<br/>            可讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_lock/) | 返回形狀的鎖定設定。<br/>            唯讀 [`IBaseShapeLock`](/slides/python-net/zh-hant/aspose.slides/ibaseshapelock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/geometryshape/is_grouped/) | 判斷此形狀是否已群組。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/geometryshape/parent_group/) | 如果形狀已群組，返回父 GroupShape 物件；否則返回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/geometryshape/slide/) | 返回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/geometryshape/presentation/) | 返回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_style/) | 返回形狀的樣式物件。<br/>            唯讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type/) | 取得或設定幾何預設類型。<br/>            注意：變更值時，所有調整值將重設為預設值。<br/>            可讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/geometryshape/adjustments/) | 返回形狀的調整值集合。<br/>            唯讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection)。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/get_image/#) | 返回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | 返回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | 將 Shape 內容另存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 內容另存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | 如果不存在，新增佔位符並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/get_base_placeholder/#) | 返回基本佔位符形狀（來自版面配置和/或母片的形狀，該形狀是當前形狀的繼承來源）。<br/>            如果當前形狀未繼承，返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/get_visual_bounds/#) | 取得根據形狀已渲染內容計算出的可視邊界。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/get_geometry_paths/#) | 返回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。<br/>             將形狀類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。<br/>             將形狀類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/geometryshape/create_shape_elements/#) | 建立並返回形狀元素的陣列。 |

### 另見
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)