---
title: Table class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/table/
---
## Table 类

表示幻灯片上的 Table。

**继承:**[`Table`](/slides/python-net/zh/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

Table 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/table/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides/table/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/table/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/table/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读/写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides/table/frame/) | 返回或设置形状框架的属性。<br/>            读/写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides/table/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线条属性的形状类型，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/table/three_d_format/) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。<br/>            注意：对于某些没有 3D 属性的形状类型，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/table/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状类型，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/table/fill_format/) | 返回一个 TableFormat.FillFormat 对象，其中包含 Table 的填充格式。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/table/hyperlink_click/) | 返回或设置鼠标点击定义的超链接。<br/>            读/写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/table/hyperlink_mouse_over/) | 返回或设置鼠标悬停定义的超链接。<br/>            读/写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/table/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh/aspose.slides/table/hidden/) | 确定形状是否隐藏。<br/>            读/写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/table/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回 Z 顺序最底部的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回 Z 顺序最顶部的形状。<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/table/connection_site_count/) | 返回形状上的连接点数量。<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides/table/rotation/) | 返回或设置指定形状绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读/写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides/table/x/) | 获取或设置形状左上角的 x 坐标，单位为点。<br/>            读/写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/table/y/) | 获取或设置形状左上角的 y 坐标，单位为点。<br/>            读/写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/table/width/) | 获取或设置形状的宽度，单位为点。<br/>            读/写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/table/height/) | 获取或设置形状的高度，单位为点。<br/>            读/写 **float**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/table/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读/写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh/aspose.slides/table/unique_id/) | 返回内部、针对演示文稿范围的标识符，供插件或其他代码使用。<br/>            由于该值可以被用户或程序重新分配，不能将其视为持久唯一键。<br/>            只读 **int**。<br/>            另请参阅 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/table/office_interop_shape_id/) | 返回幻灯片范围内的唯一标识符，在形状的整个生命周期保持不变，且 PowerPoint 或互操作代码可以从文档任何位置可靠地引用该形状。<br/>            只读 **int**。<br/>            另请参阅 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/table/alternative_text/) | 返回或设置形状的替代文字。<br/>            读/写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/table/alternative_text_title/) | 返回或设置形状的替代文字标题。<br/>            读/写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides/table/name/) | 返回或设置形状的名称。<br/>            必须不为 None。如有需要使用空字符串。<br/>            读/写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/table/is_decorative/) | 获取或设置 “标记为装饰” 选项<br/>            读/写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/table/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/table/is_grouped/) | 确定形状是否已分组。<br/>            只读 **bool**. |
| [`parent_group`](/slides/python-net/zh/aspose.slides/table/parent_group/) | 如果形状已分组，返回父 GroupShape 对象。否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides/table/slide/) | 返回形状所在的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh/aspose.slides/table/presentation/) | 返回幻灯片所在的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides/table/graphical_object_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/zh/aspose.slides/table/rows/) | 返回行集合。<br/>            只读 [`IRowCollection`](/slides/python-net/zh/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/zh/aspose.slides/table/columns/) | 返回列集合。<br/>            只读 [`IColumnCollection`](/slides/python-net/zh/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/zh/aspose.slides/table/table_format/) | 返回包含此表格格式属性的 TableFormat 对象。<br/>            只读 [`ITableFormat`](/slides/python-net/zh/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/zh/aspose.slides/table/style_preset/) | 获取或设置内置表格样式。<br/>            读/写 [`TableStylePreset`](/slides/python-net/zh/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/zh/aspose.slides/table/right_to_left/) | 确定表格是否具有从右到左的阅读顺序。<br/>            读/写 **bool**. |
| [`first_row`](/slides/python-net/zh/aspose.slides/table/first_row/) | 确定表格的首行是否需使用特殊格式绘制。<br/>            读/写 **bool**. |
| [`first_col`](/slides/python-net/zh/aspose.slides/table/first_col/) | 确定表格的首列是否需使用特殊格式绘制。<br/>            读/写 **bool**. |
| [`last_row`](/slides/python-net/zh/aspose.slides/table/last_row/) | 确定表格的末行是否需使用特殊格式绘制。<br/>            读/写 **bool**. |
| [`last_col`](/slides/python-net/zh/aspose.slides/table/last_col/) | 确定表格的末列是否需使用特殊格式绘制。<br/>            读/写 **bool**. |
| [`horizontal_banding`](/slides/python-net/zh/aspose.slides/table/horizontal_banding/) | 确定偶数行是否需使用不同的格式绘制。<br/>            读/写 **bool**. |
| [`vertical_banding`](/slides/python-net/zh/aspose.slides/table/vertical_banding/) | 确定偶数列是否需使用不同的格式绘制。<br/>            读/写 **bool**. |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/table/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/table/write_as_svg/#iorawiobase) | 将 Shape 内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将 Shape 内容保存为 SVG 文件。 |
| [`set_text_format(self, source)`](/slides/python-net/zh/aspose.slides/table/set_text_format/#iportionformat) | 将定义的段落格式属性应用于所有表格单元格的段落。 |
| [`set_text_format(self, source)`](/slides/python-net/zh/aspose.slides/table/set_text_format/#iparagraphformat) | 将定义的段落格式属性设置为所有表格单元格的段落。 |
| [`set_text_format(self, source)`](/slides/python-net/zh/aspose.slides/table/set_text_format/#itextframeformat) | 将定义的文本框格式属性设置为所有表格单元格的文本框。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/table/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/table/add_placeholder/#iplaceholder) | 如果不存在占位符，则添加新占位符并将占位符属性设置为指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/table/get_base_placeholder/#) | 返回基本占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/table/get_visual_bounds/#) | 获取根据渲染内容计算得到的形状可视边界。 |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/zh/aspose.slides/table/merge_cells/#icell-icell-bool) | 合并相邻单元格。 |

### 另请参阅
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 类 [`Table`](/slides/python-net/zh/aspose.slides/table)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)