---
title: SmartArtShape class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartartshape/
---
## SmartArtShape 類別

Represents SmartArt shape

**Inheritance:**[`SmartArtShape`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The SmartArtShape type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/is_text_holder/) | 決定形狀是否為 TextHolder_PPT。<br/>            只讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/placeholder/) | 傳回形狀的佔位符。若形狀沒有佔位符，則傳回 None。<br/>            只讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/custom_data/) | 傳回形狀的自訂資料。<br/>            只讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/frame/) | 傳回或設定形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀，可能傳回 None。<br/>            只讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/three_d_format/) | 傳回形狀的 ThreeDFormat 物件，其包含 3D 效果屬性。<br/>            註：對於某些沒有 3D 屬性的形狀，可能傳回 None。<br/>            只讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/effect_format/) | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀，可能傳回 None。<br/>            只讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/fill_format/) | 傳回包含形狀填色格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填色屬性的形狀，可能傳回 None。<br/>            只讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/hyperlink_manager/) | 傳回超連結管理器。<br/>            只讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/hidden/) | 決定形狀是否被隱藏。<br/>            可讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/z_order_position/) | 傳回形狀在 Z 次序中的位置。<br/>            Shapes[0] 傳回 Z 次序最背面的形狀，<br/>            而 Shapes[Shapes.Count - 1] 傳回 Z 次序最前面的形狀。<br/>            只讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/connection_site_count/) | 傳回形狀的連接點數量。<br/>            只讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/x/) | 取得或設定形狀左上角的 x 座標（以點為單位）。<br/>            可讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/y/) | 取得或設定形狀左上角的 y 座標（以點為單位）。<br/>            可讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            可讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            可讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/black_white_mode/) | 此屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/unique_id/) | 傳回供外掛或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能被使用者或程式重新指派，不能視為持久唯一鍵。<br/>            只讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | 傳回在投影片範圍內的唯一識別碼，於形狀的生命週期內保持不變，讓 PowerPoint 或互通程式碼能從文件任何位置可靠地參照該形狀。<br/>            只讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            可讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            可讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。必要時可使用空字串。<br/>            可讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            可讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/shape_lock/) | 傳回形狀的鎖定設定。<br/>            只讀 [`IBaseShapeLock`](/slides/python-net/zh-hant/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/is_grouped/) | 決定形狀是否已群組。<br/>            只讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/parent_group/) | 若形狀已群組，傳回其父 GroupShape 物件；否則傳回 None。<br/>            只讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/slide/) | 傳回形狀的父投影片。<br/>            只讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/presentation/) | 傳回投影片的父簡報。<br/>            只讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/shape_style/) | 傳回形狀的樣式物件。<br/>            只讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/shape_type/) | 傳回或設定幾何預設類型。<br/>            註：變更值時，所有調整值將重設為預設值。<br/>            可讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/adjustments/) | 傳回形狀的調整值集合。<br/>            只讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/text_frame/) | 傳回 SmartArt 形狀的文字。<br/>            只讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | 將形狀內容另存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容另存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | 傳回基本佔位符形狀（來自版面配置和/或母片，為目前形狀繼承自的形狀）。<br/>            若目前形狀未繼承，則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | 取得根據形狀已渲染內容計算出的視覺邊界。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。<br/>             將形狀類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。<br/>             將形狀類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape/create_shape_elements/#) | 建立並傳回形狀元素的陣列。 |

### 另請參閱
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`SmartArtShape`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 程式庫 [`Aspose.Slides`](/slides/python-net)