---
title: OleObjectFrame class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/oleobjectframe/
---
## OleObjectFrame 類別

表示投影片上的 OLE 物件。

**Inheritance:**[`OleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**。 |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/placeholder/) | 傳回形狀的占位符。如果形狀沒有占位符，則傳回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/custom_data/) | 傳回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/raw_frame/) | 傳回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/frame/) | 傳回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/line_format/) | 傳回包含形狀線條格式屬性的 LineFormat 物件。<br/>            註：對於某些沒有線條屬性的形狀，可能傳回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/three_d_format/) | 傳回形狀的 ThreeDFormat 物件（包含 3D 效果屬性）。<br/>            註：對於某些沒有 3D 屬性的形狀，可能傳回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/effect_format/) | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            註：對於某些沒有效果屬性的形狀，可能傳回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/fill_format/) | 傳回包含形狀填充格式屬性的 FillFormat 物件。<br/>            註：對於某些沒有填充屬性的形狀，可能傳回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/hyperlink_click/) | 傳回或設定滑鼠點擊時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | 傳回或設定滑鼠懸停時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/hyperlink_manager/) | 傳回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/hidden/) | 判斷形狀是否為隱藏。<br/>            讀寫 **bool**。 |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/z_order_position/) | 傳回形狀在 Z 軸順序中的位置。<br/>            Shapes[0] 會傳回位於 Z 軸最底層的形狀，<br/>            而 Shapes[Shapes.Count - 1] 會傳回位於 Z 軸最前端的形狀。<br/>            唯讀 **int**。 |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/connection_site_count/) | 傳回形狀的連接點數量。<br/>            唯讀 **int**。 |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/rotation/) | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。<br/>            讀寫 **float**。 |
| [`x`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/x/) | 取得或設定形狀左上角的 X 坐標（點為單位）。<br/>            讀寫 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/y/) | 取得或設定形狀左上角的 Y 坐標（點為單位）。<br/>            讀寫 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/width/) | 取得或設定形狀的寬度（點為單位）。<br/>            讀寫 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/height/) | 取得或設定形狀的高度（點為單位）。<br/>            讀寫 **float**。 |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/black_white_mode/) | 此屬性指定形狀在黑白顯示模式下的渲染方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/unique_id/) | 傳回供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。<br/>            因為此值可能由使用者或程式重新指派，不能將其視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/office_interop_shape_id/) | 傳回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 Interop 程式碼能從文件任何位置可靠地參照此形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/alternative_text/) | 傳回或設定與形狀相關聯的替代文字。<br/>            讀寫 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/alternative_text_title/) | 傳回或設定與形狀相關聯的替代文字標題。<br/>            讀寫 **str**。 |
| [`name`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/name/) | 傳回或設定形狀的名稱。<br/>            必須非 None。如有需要，可使用空字串。<br/>            讀寫 **str**。 |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/is_decorative/) | 取得或設定「標記為裝飾」選項。<br/>            讀寫 **bool**。 |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/shape_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/is_grouped/) | 判斷形狀是否為群組。<br/>            唯讀 **bool**。 |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/parent_group/) | 如果形狀被群組，傳回其父 GroupShape 物件；否則傳回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/slide/) | 傳回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/presentation/) | 傳回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/graphical_object_lock/) | 傳回形狀的鎖定設定。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock)。 |
| [`substitute_picture_format`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/substitute_picture_format/) | 傳回 OleObject 圖像填充屬性物件。<br/>            唯讀 [`IPictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat)。 |
| [`substitute_picture_title`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/substitute_picture_title/) | 傳回或設定 OleObject 圖示的標題。<br/>            讀寫 **str**。 |
| [`object_name`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/object_name/) | 傳回或設定物件的名稱。<br/>            讀寫 **str**。 |
| [`object_prog_id`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/object_prog_id/) | 傳回物件的 ProgID。<br/>            唯讀 **str**。 |
| [`link_file_name`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/link_file_name/) | 傳回連結檔案的完整路徑，將使用短檔名。<br/>            唯讀 **str**。 |
| [`link_path_long`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/link_path_long/) | 傳回連結檔案的完整路徑，將使用長檔名。<br/>            讀寫 **str**。 |
| [`link_path_relative`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/link_path_relative/) | 若存在連結檔案，傳回其相對路徑；否則傳回空字串。<br/>            唯讀 **str**。 |
| [`embedded_file_label`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/embedded_file_label/) | 傳回內嵌 OLE 物件的檔案名稱 |
| [`embedded_file_name`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/embedded_file_name/) | 傳回內嵌 OLE 物件的路徑 |
| [`embedded_data`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/embedded_data/) | 取得或設定 OLE 內嵌資料的資訊。<br/>            讀寫 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)。 |
| [`is_object_icon`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/is_object_icon/) | 判斷物件是否以圖示方式顯示。<br/>            讀寫 **bool**。 |
| [`is_object_link`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/is_object_link/) | 判斷物件是否連結至外部檔案。<br/>            唯讀 **bool**。 |
| [`update_automatic`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/update_automatic/) | 判斷連結的內嵌物件在簡報開啟或列印時是否自動更新。<br/>            讀寫 **bool**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/get_image/#) | 傳回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | 傳回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | 將形狀內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/remove_placeholder/#) | 定義此形狀不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | 如果不存在，則新增一個占位符，並將占位符屬性設定為指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/get_base_placeholder/#) | 傳回基本的占位符形狀（從版面配置或母版投影片繼承而來的形狀）。<br/>            若目前形狀未繼承，則傳回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/get_visual_bounds/#) | 取得根據渲染內容計算出的形狀視覺邊界。 |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | 設定 OLE 內嵌資料的資訊。<br/>            <br/>            此方法會變更物件的屬性以符合新資料，並將 IsObjectLink 旗標設為 false，表示 OLE 物件已內嵌。 |

### 另見
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`OleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)