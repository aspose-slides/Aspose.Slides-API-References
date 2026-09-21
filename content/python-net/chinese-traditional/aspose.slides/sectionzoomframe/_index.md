---
title: SectionZoomFrame class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame 類別

表示投影片中的 Section Zoom 物件。

**繼承:**[`SectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

SectionZoomFrame 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/placeholder/) | 取得形狀的佔位符。若形狀沒有佔位符，返回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/custom_data/) | 取得形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/raw_frame/) | 取得或設定原始形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/frame/) | 取得或設定形狀框架的屬性。<br/>            可讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/line_format/) | 取得包含形狀線條格式屬性的 LineFormat 物件。<br/>            註: 對於某些沒有線條屬性的形狀，可能回傳 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/three_d_format/) | 取得包含形狀 3D 效果屬性的 ThreeDFormat 物件。<br/>            註: 對於某些沒有 3D 屬性的形狀，可能回傳 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/effect_format/) | 取得包含套用於形狀之像素效果的 EffectFormat 物件。<br/>            註: 對於某些沒有效果屬性的形狀，可能回傳 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/fill_format/) | 取得包含形狀填色格式屬性的 FillFormat 物件。<br/>            註: 對於某些沒有填色屬性的形狀，可能回傳 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/hyperlink_click/) | 取得或設定滑鼠點擊時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | 取得或設定滑鼠懸停時的超連結。<br/>            可讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/hyperlink_manager/) | 取得超連結管理員。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/hidden/) | 判斷形狀是否隱藏。<br/>            可讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/z_order_position/) | 取得形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 取得 Z 軸順序最底層的形狀，<br/>            Shapes[Shapes.Count - 1] 取得 Z 軸順序最前端的形狀。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/connection_site_count/) | 取得形狀的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/rotation/) | 取得或設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            可讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/x/) | 取得或設定形狀左上角的 X 座標（單位：點）。<br/>            可讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/y/) | 取得或設定形狀左上角的 Y 座標（單位：點）。<br/>            可讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/width/) | 取得或設定形狀的寬度（單位：點）。<br/>            可讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/height/) | 取得或設定形狀的高度（單位：點）。<br/>            可讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            可讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/unique_id/) | 取得供外掛或其他程式碼使用的內部、簡報範圍識別碼。<br/>            由於此值可能由使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/office_interop_shape_id/) | 取得簡報範圍內唯一且在形狀生命週期內保持不變的識別碼，PowerPoint 或 interop 程式碼可可靠地從文件任何位置參照此形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/alternative_text/) | 取得或設定與形狀關聯的替代文字。<br/>            可讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/alternative_text_title/) | 取得或設定與形狀關聯的替代文字標題。<br/>            可讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/name/) | 取得或設定形狀的名稱。<br/>            必須非 None。必要時可使用空字串。<br/>            可讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/is_decorative/) | 取得或設定「標示為裝飾」選項。<br/>            可讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/shape_lock/) | 取得形狀的鎖定資訊。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/is_grouped/) | 判斷形狀是否為群組的一部分。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/parent_group/) | 若形狀為群組的一部份，返回其父層 GroupShape 物件；否則返回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/slide/) | 取得形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/presentation/) | 取得投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/graphical_object_lock/) | 取得形狀的鎖定資訊。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`image_type`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/image_type/) | 取得或設定 Zoom 物件的影像類型。<br/>            可讀寫 [`ZoomImageType`](/slides/python-net/zh-hant/aspose.slides/zoomimagetype)。<br/>            預設值: Preview |
| [`return_to_parent`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/return_to_parent/) | 取得或設定投影片放映時的導覽行為。<br/>            可讀寫 **bool**。<br/>            預設值: false |
| [`show_background`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/show_background/) | 取得或設定 Zoom 是否使用目標投影片的背景。<br/>            可讀寫 **bool**。<br/>            預設值: true |
| [`zoom_image`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/zoom_image/) | 取得或設定 Zoom 物件的影像。<br/>            可讀寫 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |
| [`transition_duration`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/transition_duration/) | 取得或設定 Zoom 與投影片之間過渡的持續時間。<br/>            可讀寫 **float**。<br/>            預設值: 1.0f |
| [`target_section`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/target_section/) | 取得或設定 Section Zoom 物件所連結的節 (section) 物件。<br/>            可讀寫 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/get_image/#) | 回傳形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | 回傳形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | 將形狀內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | 若無佔位符則新增，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/get_base_placeholder/#) | 回傳基本佔位符形狀（來自版面配置或母片投影片的形狀，當前形狀繼承自該形狀）。<br/>            若當前形狀未繼承，則返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe/get_visual_bounds/#) | 取得根據形狀已呈現內容計算出的視覺邊界。 |

### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`SectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)