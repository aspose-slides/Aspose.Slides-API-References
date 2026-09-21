---
title: Connector class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/connector/
---
## Connector 類別

表示一個連接線。

**繼承:**[`Connector`](/slides/python-net/zh-hant/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

Connector 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/connector/is_text_holder/) | 判斷此形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/connector/placeholder/) | 傳回形狀的佔位符。如果形狀沒有佔位符，傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/connector/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/connector/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/connector/frame/) | 傳回或設定形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/connector/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/connector/three_d_format/) | 傳回形狀的 ThreeDFormat 物件，用於 3d 效果屬性。<br/>            註：對於某些沒有 3d 屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/connector/effect_format/) | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/connector/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀類型，可能傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/connector/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/connector/hyperlink_mouse_over/) | 傳回或設定滑鼠移過時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/connector/hyperlink_manager/) | 傳回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/connector/hidden/) | 判斷形狀是否隱藏。<br/>            可讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/connector/z_order_position/) | 傳回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 會傳回位於 Z 軸順序最底層的形狀，<br/>            而 Shapes[Shapes.Count - 1] 會傳回位於最前端的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/connector/connection_site_count/) | 傳回形狀上的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/connector/rotation/) | 傳回或設定指定形狀繞<br/>            z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/connector/x/) | 取得或設定形狀左上角的 X 座標，單位為點。<br/>            可讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/connector/y/) | 取得或設定形狀左上角的 Y 座標，單位為點。<br/>            可讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/connector/width/) | 取得或設定形狀的寬度，單位為點。<br/>            可讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/connector/height/) | 取得或設定形狀的高度，單位為點。<br/>            可讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/connector/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/connector/unique_id/) | 傳回內部、針對簡報範圍的識別碼，供外掛或其他程式碼使用。<br/>            由於使用者或程式可以重新指派此值，不能將其視為永久的唯一鍵。<br/>            唯讀 **int**.<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/connector/office_interop_shape_id/) | 傳回以投影片為範圍的唯一識別碼，在形狀生命週期內保持不變，並讓 PowerPoint 或 interop 程式碼能在文件任何位置可靠地引用該形狀。<br/>            唯讀 **int**.<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/connector/alternative_text/) | 傳回或設定與形狀關聯的替代文字。<br/>            可讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/connector/alternative_text_title/) | 傳回或設定與形狀關聯的替代文字標題。<br/>            可讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/connector/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。如有需要可使用空字串。<br/>            可讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/connector/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            可讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/connector/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IConnectorLock`](/slides/python-net/zh-hant/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/connector/is_grouped/) | 判斷形狀是否已群組。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/connector/parent_group/) | 如果形狀已群組，傳回父級 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/connector/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/connector/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/zh-hant/aspose.slides/connector/shape_style/) | 傳回形狀的樣式物件。<br/>            唯讀 [`IShapeStyle`](/slides/python-net/zh-hant/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/zh-hant/aspose.slides/connector/shape_type/) | 傳回或設定 AutoShape 類型。<br/>            可讀寫 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/zh-hant/aspose.slides/connector/adjustments/) | 傳回形狀的調整值集合。<br/>            唯讀 [`IAdjustValueCollection`](/slides/python-net/zh-hant/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/zh-hant/aspose.slides/connector/connector_lock/) | 傳回連接線的鎖定設定。<br/>            唯讀 [`IConnectorLock`](/slides/python-net/zh-hant/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/zh-hant/aspose.slides/connector/start_shape_connected_to/) | 傳回或設定連接線起點所附著的形狀。<br/>            可讀寫 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/zh-hant/aspose.slides/connector/end_shape_connected_to/) | 傳回或設定連接線終點所附著的形狀。<br/>            可讀寫 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/zh-hant/aspose.slides/connector/start_shape_connection_site_index/) | 傳回或設定起始形狀的連接點索引。<br/>            可讀寫 **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/zh-hant/aspose.slides/connector/end_shape_connection_site_index/) | 傳回或設定結束形狀的連接點索引。<br/>            可讀寫 **int**. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/connector/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/connector/write_as_svg/#iorawiobase) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將 Shape 內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/connector/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/connector/add_placeholder/#iplaceholder) | 若沒有佔位符，則新增一個，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/connector/get_base_placeholder/#) | 傳回基本佔位符形狀（來自版面配置及/或母片，且為目前形狀所繼承的形狀）。<br/>            若目前形狀未被繼承，則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/connector/get_visual_bounds/#) | 取得根據形狀已渲染內容計算出的視覺邊界。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh-hant/aspose.slides/connector/get_geometry_paths/#) | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh-hant/aspose.slides/connector/set_geometry_path/#igeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左<br/>             上角。<br/>             將形狀的類型（[`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)）變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh-hant/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | 從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左<br/>             上角。<br/>             將形狀的類型（[`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)）變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh-hant/aspose.slides/connector/create_shape_elements/#) | 建立並傳回形狀元素的陣列。 |
| [`reroute(self)`](/slides/python-net/zh-hant/aspose.slides/connector/reroute/#) | 重新路由連接線，使其在所連接的形狀之間採取最短路徑。 |

### 另請參閱
* 類別 [`Connector`](/slides/python-net/zh-hant/aspose.slides/connector)
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)