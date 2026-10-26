---
title: Chart class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.charts/chart/
---
## Chart 类

表示幻灯片上的图形图表。

**继承:**[`Chart`](/slides/python-net/zh/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

Chart 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides.charts/chart/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**。 |
| [`placeholder`](/slides/python-net/zh/aspose.slides.charts/chart/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides.charts/chart/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh/aspose.slides.charts/chart/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh/aspose.slides.charts/chart/frame/) | 返回或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh/aspose.slides.charts/chart/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线条属性的形状，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh/aspose.slides.charts/chart/three_d_format/) | 返回包含形状三维效果属性的 ThreeDFormat 对象。<br/>            注意：对于某些没有 3d 属性的形状，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides.charts/chart/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides.charts/chart/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对于某些没有填充属性的形状，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides.charts/chart/hyperlink_click/) | 返回或设置鼠标点击时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides.charts/chart/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides.charts/chart/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh/aspose.slides.charts/chart/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**。 |
| [`z_order_position`](/slides/python-net/zh/aspose.slides.charts/chart/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回 Z 顺序最靠后的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回 Z 顺序最前面的形状。<br/>            只读 **int**。 |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides.charts/chart/connection_site_count/) | 返回形状上的连接点数量。<br/>            只读 **int**。 |
| [`rotation`](/slides/python-net/zh/aspose.slides.charts/chart/rotation/) | 返回或设置指定形状围绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**。 |
| [`x`](/slides/python-net/zh/aspose.slides.charts/chart/x/) | 获取或设置形状左上角的 X 坐标，以点为单位。<br/>            读写 **float**。 |
| [`y`](/slides/python-net/zh/aspose.slides.charts/chart/y/) | 获取或设置形状左上角的 Y 坐标，以点为单位。<br/>            读写 **float**。 |
| [`width`](/slides/python-net/zh/aspose.slides.charts/chart/width/) | 获取或设置形状的宽度，以点为单位。<br/>            读写 **float**。 |
| [`height`](/slides/python-net/zh/aspose.slides.charts/chart/height/) | 获取或设置形状的高度，以点为单位。<br/>            读写 **float**。 |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides.charts/chart/black_white_mode/) | 属性指定形状在黑白显示模式下的呈现方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh/aspose.slides.charts/chart/unique_id/) | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。<br/>            因为此值可能被用户或程序重新分配，不能将其视为持久唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides.charts/chart/office_interop_shape_id/) | 返回幻灯片范围的唯一标识符，在形状的整个生命周期内保持不变，PowerPoint 或互操作代码可以可靠地从文档任何位置引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh/aspose.slides.charts/chart/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            读写 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides.charts/chart/alternative_text_title/) | 返回或设置与形状关联的替代文本标题。<br/>            读写 **str**。 |
| [`name`](/slides/python-net/zh/aspose.slides.charts/chart/name/) | 返回或设置形状的名称。<br/>            必须不为 None。如有需要请使用空字符串。<br/>            读写 **str**。 |
| [`is_decorative`](/slides/python-net/zh/aspose.slides.charts/chart/is_decorative/) | 获取或设置 “标记为装饰” 选项<br/>            读写 **bool**。 |
| [`shape_lock`](/slides/python-net/zh/aspose.slides.charts/chart/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh/aspose.slides.charts/chart/is_grouped/) | 确定形状是否已分组。<br/>            只读 **bool**。 |
| [`parent_group`](/slides/python-net/zh/aspose.slides.charts/chart/parent_group/) | 如果形状已分组，返回父 GroupShape 对象。否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/chart/slide/) | 返回形状所在的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/chart/presentation/) | 返回幻灯片所在的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides.charts/chart/graphical_object_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock)。 |
| [`plot_visible_cells_only`](/slides/python-net/zh/aspose.slides.charts/chart/plot_visible_cells_only/) | 确定是否仅绘制可见单元格。设为 False 时绘制可见和隐藏单元格。<br/>            读写 **bool**。 |
| [`display_blanks_as`](/slides/python-net/zh/aspose.slides.charts/chart/display_blanks_as/) | 返回或设置在图表上绘制空白单元格的方式。<br/>            读写 [`DisplayBlanksAsType`](/slides/python-net/zh/aspose.slides.charts/displayblanksastype)。 |
| [`chart_data`](/slides/python-net/zh/aspose.slides.charts/chart/chart_data/) | 返回有关与图表关联的链接或嵌入数据的信息。<br/>            只读 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)。 |
| [`has_title`](/slides/python-net/zh/aspose.slides.charts/chart/has_title/) | 确定图表是否具有可见标题。<br/>            读写 **bool**。 |
| [`chart_title`](/slides/python-net/zh/aspose.slides.charts/chart/chart_title/) | 返回或设置图表标题。<br/>            只读 [`IChartTitle`](/slides/python-net/zh/aspose.slides.charts/icharttitle)。 |
| [`has_data_table`](/slides/python-net/zh/aspose.slides.charts/chart/has_data_table/) | 确定图表是否包含数据表。<br/>            读写 **bool**。 |
| [`has_legend`](/slides/python-net/zh/aspose.slides.charts/chart/has_legend/) | 确定图表是否具有图例。<br/>            读写 **bool**。 |
| [`legend`](/slides/python-net/zh/aspose.slides.charts/chart/legend/) | 返回或设置图表的图例。<br/>            只读 [`ILegend`](/slides/python-net/zh/aspose.slides.charts/ilegend)。 |
| [`chart_data_table`](/slides/python-net/zh/aspose.slides.charts/chart/chart_data_table/) | 返回图表的数据表。<br/>            只读 [`IDataTable`](/slides/python-net/zh/aspose.slides.charts/idatatable)。 |
| [`style`](/slides/python-net/zh/aspose.slides.charts/chart/style/) | 返回或设置图表样式。<br/>            读写 [`StyleType`](/slides/python-net/zh/aspose.slides.charts/styletype)。 |
| [`type`](/slides/python-net/zh/aspose.slides.charts/chart/type/) | 返回或设置图表类型。<br/>            读写 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype)。 |
| [`plot_area`](/slides/python-net/zh/aspose.slides.charts/chart/plot_area/) | 表示图表的绘图区域。<br/>            只读 [`IChartPlotArea`](/slides/python-net/zh/aspose.slides.charts/ichartplotarea)。 |
| [`rotation_3d`](/slides/python-net/zh/aspose.slides.charts/chart/rotation_3d/) | 返回图表的 3D 旋转。<br/>            只读 [`IRotation3D`](/slides/python-net/zh/aspose.slides.charts/irotation3d)。 |
| [`back_wall`](/slides/python-net/zh/aspose.slides.charts/chart/back_wall/) | 返回一个对象，可更改 3D 图表后壁的格式。<br/>            只读 [`IChartWall`](/slides/python-net/zh/aspose.slides.charts/ichartwall)。 |
| [`side_wall`](/slides/python-net/zh/aspose.slides.charts/chart/side_wall/) | 返回一个对象，可更改 3D 图表侧壁的格式。<br/>            只读 [`IChartWall`](/slides/python-net/zh/aspose.slides.charts/ichartwall)。 |
| [`floor`](/slides/python-net/zh/aspose.slides.charts/chart/floor/) | 返回一个对象，可更改 3D 图表底面的格式。<br/>            只读 [`IChartWall`](/slides/python-net/zh/aspose.slides.charts/ichartwall)。 |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/chart/text_format/) | 返回图表文本格式。<br/>            以下类型不适用此属性：[`ChartType.TREEMAP`](/slides/python-net/zh/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/zh/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/zh/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/zh/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/zh/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/zh/aspose.slides.charts/charttype/BOX_AND_WHISKER)。<br/>            只读 [`IChartTextFormat`](/slides/python-net/zh/aspose.slides.charts/icharttextformat)。 |
| [`theme_manager`](/slides/python-net/zh/aspose.slides.charts/chart/theme_manager/) | 返回主题管理器。<br/>            只读 [`IOverrideThemeManager`](/slides/python-net/zh/aspose.slides.theme/ioverridethememanager)。 |
| [`user_shapes`](/slides/python-net/zh/aspose.slides.charts/chart/user_shapes/) | 指定绘制在图表之上的形状。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。 |
| [`axes`](/slides/python-net/zh/aspose.slides.charts/chart/axes/) | 提供对图表坐标轴的访问。<br/>            只读 [`IAxesManager`](/slides/python-net/zh/aspose.slides.charts/iaxesmanager)。 |
| [`show_data_labels_over_maximum`](/slides/python-net/zh/aspose.slides.charts/chart/show_data_labels_over_maximum/) | 指定是否在图表最大值上方显示数据标签。<br/>            读写 **bool**。 |
| [`has_rounded_corners`](/slides/python-net/zh/aspose.slides.charts/chart/has_rounded_corners/) | 指定图表区域应具有圆角。<br/>            读写 **bool**。 |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/chart/chart/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides.charts/chart/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | 将形状内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将形状内容保存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides.charts/chart/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | 如果不存在，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides.charts/chart/get_base_placeholder/#) | 返回基本占位符形状（从布局和/或母版幻灯片中继承的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides.charts/chart/get_visual_bounds/#) | 获取根据渲染内容计算的形状可视边界。 |
| [`validate_chart_layout(self)`](/slides/python-net/zh/aspose.slides.charts/chart/validate_chart_layout/#) | 计算图表元素的实际值。实际值包括实现 IActualLayout 接口的元素位置 <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            以及轴的实际值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)。 |
| [`create_theme_effective(self)`](/slides/python-net/zh/aspose.slides.charts/chart/create_theme_effective/#) | 返回此图表的有效主题。 |

### 另见
* 类 [`Chart`](/slides/python-net/zh/aspose.slides.charts/chart)
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)