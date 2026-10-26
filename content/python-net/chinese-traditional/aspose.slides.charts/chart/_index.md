---
title: Chart class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chart/
---
## Chart 類別

代表投影片上的圖形圖表。

**Inheritance:**[`Chart`](/slides/python-net/zh-hant/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

Chart 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides.charts/chart/is_text_holder/) | 判斷形狀是否為 TextHolder_PPT。<br/>            唯讀 **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides.charts/chart/placeholder/) | 返回形狀的佔位符。如果形狀沒有佔位符，返回 None。<br/>            唯讀 [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides.charts/chart/custom_data/) | 返回形狀的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides.charts/chart/raw_frame/) | 返回或設定原始形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides.charts/chart/frame/) | 返回或設定形狀框架的屬性。<br/>            讀寫 [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides.charts/chart/line_format/) | 返回包含形狀線條格式屬性的 LineFormat 物件。<br/>            注意：對於某些沒有線條屬性的形狀，可能返回 None。<br/>            唯讀 [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides.charts/chart/three_d_format/) | 返回形狀的 3D 效果屬性 ThreeDFormat 物件。<br/>            注意：對於某些沒有 3D 屬性的形狀，可能返回 None。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides.charts/chart/effect_format/) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。<br/>            注意：對於某些沒有效果屬性的形狀，可能返回 None。<br/>            唯讀 [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides.charts/chart/fill_format/) | 返回包含形狀填充格式屬性的 FillFormat 物件。<br/>            注意：對於某些沒有填充屬性的形狀，可能返回 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides.charts/chart/hyperlink_click/) | 返回或設定滑鼠點擊時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides.charts/chart/hyperlink_mouse_over/) | 返回或設定滑鼠懸停時的超連結。<br/>            讀寫 [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides.charts/chart/hyperlink_manager/) | 返回超連結管理器。<br/>            唯讀 [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides.charts/chart/hidden/) | 判斷形狀是否為隱藏。<br/>            讀寫 **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides.charts/chart/z_order_position/) | 返回形狀在 Z 序的位階。<br/>            Shapes[0] 返回位於 Z 序最後面的形狀，<br/>            而 Shapes[Shapes.Count - 1] 返回位於 Z 序最前面的形狀。<br/>            唯讀 **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides.charts/chart/connection_site_count/) | 返回形狀的連接點數量。<br/>            唯讀 **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides.charts/chart/rotation/) | 返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。<br/>            正值表示順時針旋轉；負值表示逆時針旋轉。<br/>            讀寫 **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides.charts/chart/x/) | 取得或設定形狀左上角的 X 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides.charts/chart/y/) | 取得或設定形狀左上角的 Y 座標（以點為單位）。<br/>            讀寫 **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides.charts/chart/width/) | 取得或設定形狀的寬度（以點為單位）。<br/>            讀寫 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides.charts/chart/height/) | 取得或設定形狀的高度（以點為單位）。<br/>            讀寫 **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides.charts/chart/black_white_mode/) | 屬性指定形狀在黑白顯示模式下的呈現方式。<br/>            讀寫 [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides.charts/chart/unique_id/) | 返回供外掛或其他程式碼使用的內部、以簡報為範圍的識別碼。<br/>            由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides.charts/chart/office_interop_shape_id/) | 返回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 interop 程式碼能在文件任何位置可靠地參照該形狀。<br/>            唯讀 **int**。<br/>            另請參閱 [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides.charts/chart/alternative_text/) | 返回或設定與形狀關聯的替代文字。<br/>            讀寫 **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides.charts/chart/alternative_text_title/) | 返回或設定與形狀關聯的替代文字標題。<br/>            讀寫 **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides.charts/chart/name/) | 返回或設定形狀的名稱。<br/>            必須非 None。如有需要可使用空字串。<br/>            讀寫 **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides.charts/chart/is_decorative/) | 取得或設定「標記為裝飾」選項<br/>            讀寫 **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides.charts/chart/shape_lock/) | 返回形狀的鎖定屬性。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides.charts/chart/is_grouped/) | 判斷形狀是否已群組。<br/>            唯讀 **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides.charts/chart/parent_group/) | 如果形狀已群組，返回父級 GroupShape 物件；否則返回 None。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides.charts/chart/slide/) | 返回形狀的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides.charts/chart/presentation/) | 返回投影片的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides.charts/chart/graphical_object_lock/) | 返回形狀的鎖定屬性。<br/>            唯讀 [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/zh-hant/aspose.slides.charts/chart/plot_visible_cells_only/) | 判斷是否僅繪製可見儲存格。若為 False，則同時繪製可見與隱藏儲存格。<br/>            讀寫 **bool**. |
| [`display_blanks_as`](/slides/python-net/zh-hant/aspose.slides.charts/chart/display_blanks_as/) | 返回或設定圖表繪製空白儲存格的方式。<br/>            讀寫 [`DisplayBlanksAsType`](/slides/python-net/zh-hant/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/zh-hant/aspose.slides.charts/chart/chart_data/) | 返回與圖表相關的連結或內嵌資料資訊。<br/>            唯讀 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/zh-hant/aspose.slides.charts/chart/has_title/) | 判斷圖表是否具有可見標題。<br/>            讀寫 **bool**. |
| [`chart_title`](/slides/python-net/zh-hant/aspose.slides.charts/chart/chart_title/) | 返回或設定圖表標題。<br/>            唯讀 [`IChartTitle`](/slides/python-net/zh-hant/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/zh-hant/aspose.slides.charts/chart/has_data_table/) | 判斷圖表是否具有資料表。<br/>            讀寫 **bool**. |
| [`has_legend`](/slides/python-net/zh-hant/aspose.slides.charts/chart/has_legend/) | 判斷圖表是否具有圖例。<br/>            讀寫 **bool**. |
| [`legend`](/slides/python-net/zh-hant/aspose.slides.charts/chart/legend/) | 返回或設定圖表的圖例。<br/>            唯讀 [`ILegend`](/slides/python-net/zh-hant/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/zh-hant/aspose.slides.charts/chart/chart_data_table/) | 返回圖表的資料表。<br/>            唯讀 [`IDataTable`](/slides/python-net/zh-hant/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/zh-hant/aspose.slides.charts/chart/style/) | 返回或設定圖表樣式。<br/>            讀寫 [`StyleType`](/slides/python-net/zh-hant/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/zh-hant/aspose.slides.charts/chart/type/) | 返回或設定圖表類型。<br/>            讀寫 [`ChartType`](/slides/python-net/zh-hant/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/zh-hant/aspose.slides.charts/chart/plot_area/) | 代表圖表的繪圖區域。<br/>            唯讀 [`IChartPlotArea`](/slides/python-net/zh-hant/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/zh-hant/aspose.slides.charts/chart/rotation_3d/) | 返回圖表的 3D 旋轉。<br/>            唯讀 [`IRotation3D`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/zh-hant/aspose.slides.charts/chart/back_wall/) | 返回允許變更 3D 圖表背壁格式的物件。<br/>            唯讀 [`IChartWall`](/slides/python-net/zh-hant/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/zh-hant/aspose.slides.charts/chart/side_wall/) | 返回允許變更 3D 圖表側壁格式的物件。<br/>            唯讀 [`IChartWall`](/slides/python-net/zh-hant/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/zh-hant/aspose.slides.charts/chart/floor/) | 返回允許變更 3D 圖表底面格式的物件。<br/>            唯讀 [`IChartWall`](/slides/python-net/zh-hant/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/zh-hant/aspose.slides.charts/chart/text_format/) | 返回圖表文字格式。<br/>            此屬性不適用於以下類型：[`ChartType.TREEMAP`](/slides/python-net/zh-hant/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/zh-hant/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/zh-hant/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/zh-hant/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/zh-hant/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/zh-hant/aspose.slides.charts/charttype/BOX_AND_WHISKER)。<br/>            唯讀 [`IChartTextFormat`](/slides/python-net/zh-hant/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides.charts/chart/theme_manager/) | 返回主題管理器。<br/>            唯讀 [`IOverrideThemeManager`](/slides/python-net/zh-hant/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/zh-hant/aspose.slides.charts/chart/user_shapes/) | 指定繪製在圖表上方的形狀。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/zh-hant/aspose.slides.charts/chart/axes/) | 提供對圖表軸的存取。<br/>            唯讀 [`IAxesManager`](/slides/python-net/zh-hant/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/zh-hant/aspose.slides.charts/chart/show_data_labels_over_maximum/) | 指定是否顯示圖表最大值以上的資料標籤。<br/>            讀寫 **bool**. |
| [`has_rounded_corners`](/slides/python-net/zh-hant/aspose.slides.charts/chart/has_rounded_corners/) | 指定圖表區域是否具有圓角。<br/>            讀寫 **bool**. |
| [`chart`](/slides/python-net/zh-hant/aspose.slides.charts/chart/chart/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/get_image/#) | 返回形狀縮圖。<br/>            預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | 返回形狀縮圖。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | 將形狀內容儲存為 SVG 檔案。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 將形狀內容儲存為 SVG 檔案。 |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/remove_placeholder/#) | 定義此形狀不是佔位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/get_base_placeholder/#) | 返回基本佔位符形狀（從版面配置或母片投影片繼承的形狀）。<br/>            若目前形狀未繼承，則返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/get_visual_bounds/#) | 取得根據形狀渲染內容計算出的視覺邊界。 |
| [`validate_chart_layout(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/validate_chart_layout/#) | 計算圖表元素的實際值。實際值包括實作 IActualLayout 介面的元素位置 <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            以及實際軸值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)。 |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides.charts/chart/create_theme_effective/#) | 返回此圖表的有效主題。 |

### 另請參閱
* 類別 [`Chart`](/slides/python-net/zh-hant/aspose.slides.charts/chart)
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)