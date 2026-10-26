---
title: SmartArt class
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartart/
---
## SmartArt 類別

代表 SmartArt 圖表

**Inheritance:**[`SmartArt`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

SmartArt 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            只讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/placeholder/) | 返回形狀的佔位符。如果形狀沒有佔位符，返回 None。<br/>            只讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/custom_data/) | 返回形狀的自訂資料。<br/>            只讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/raw_frame/) | 返回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/frame/) | 返回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/line_format/) | 返回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀類型，可能返回 None。<br/>            只讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/three_d_format/) | 返回包含形狀 3D 效果屬性的 ThreeDFormat 物件。<br/>            註：對於某些沒有 3D 屬性的形狀類型，可能返回 None。<br/>            只讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/effect_format/) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀類型，可能返回 None。<br/>            只讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/fill_format/) | 返回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀類型，可能返回 None。<br/>            只讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/hyperlink_click/) | 返回或設定滑鼠點擊時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | 返回或設定滑鼠懸停時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/hyperlink_manager/) | 返回超連結管理器。<br/>            只讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/hidden/) | 判斷形狀是否被隱藏。<br/>            讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/z_order_position/) | 返回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 會返回位於 Z 軸順序最背後的形狀，<br/>            而 Shapes[Shapes.Count - 1] 會返回位於 Z 軸順序最前面的形狀。<br/>            只讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/connection_site_count/) | 返回形狀的連接點數量。<br/>            只讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/rotation/) | 返回或設定指定形狀繞 Z 軸旋轉的角度（度）。<br/>            正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/x/) | 取得或設定形狀左上角的 x 座標（以點為單位）。<br/>            讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/y/) | 取得或設定形狀左上角的 y 座標（以點為單位）。<br/>            讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/black_white_mode/) | 此屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/unique_id/) | 返回供外掛或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能被使用者或程式重新指派，不能視為永久的唯一鍵。<br/>            只讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/office_interop_shape_id/) | 返回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式碼能可靠地從文件任何位置參照該形狀。<br/>            只讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/alternative_text/) | 返回或設定與形狀相關聯的替代文字。<br/>            讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/alternative_text_title/) | 返回或設定與形狀相關聯的替代文字標題。<br/>            讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/name/) | 返回或設定形狀的名稱。<br/>            必須非 None。如有需要可使用空字串。<br/>            讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/shape_lock/) | 返回形狀的鎖定設定。<br/>            只讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/is_grouped/) | 判斷形狀是否已群組。<br/>            只讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/parent_group/) | 如果形狀已群組，返回父 GroupShape 物件；否則返回 None。<br/>            只讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/slide/) | 返回形狀所在的父投影片。<br/>            只讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/presentation/) | 返回投影片所在的父簡報。<br/>            只讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/graphical_object_lock/) | 返回形狀的鎖定設定。<br/>            只讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`all_nodes`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/all_nodes/) | 返回 SmartArt 物件中所有節點的集合。<br/>            只讀 [`ISmartArtNodeCollection`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnodecollection)。 |
| [`nodes`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/nodes/) | 返回 SmartArt 物件中根節點的集合。<br/>            只讀 [`ISmartArtNodeCollection`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnodecollection)。 |
| [`layout`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/layout/) | 返回或設定 SmartArt 物件的版面配置。<br/>            讀寫 [`SmartArtLayoutType`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartlayouttype)。 |
| [`quick_style`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/quick_style/) | 返回或設定 SmartArt 物件的快速樣式。<br/>            讀寫 [`SmartArtQuickStyleType`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartquickstyletype)。 |
| [`color_style`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/color_style/) | 返回或設定 SmartArt 物件的顏色樣式。<br/>            讀寫 [`SmartArtColorType`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartcolortype)。 |
| [`is_reversed`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/is_reversed/) | 返回或設定 SmartArt 圖表的文字方向狀態（左至右 LTR 或右至左 RTL），前提是圖表支援方向翻轉。<br/>            讀寫 **bool**。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/get_image/#) | 返回形狀的縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | 返回形狀的縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | 將形狀的內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀的內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | 如果不存在，新增一個佔位符並將佔位符屬性設定為指定的值。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/get_base_placeholder/#) | 返回基本佔位符形狀（來自版面配置和/或母片的形狀，供目前形狀繼承）。<br/>            如果目前形狀未繼承，則返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart/get_visual_bounds/#) | 取得根據形狀渲染內容計算的可視邊界。 |

### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`SmartArt`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)