---
title: AutoShape class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/autoshape/
---
## AutoShape class

表示一个 AutoShape。

**Inheritance:**[`AutoShape`](/slides/python-net/zh/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/zh/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

AutoShape 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/autoshape/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**。 |
| [`placeholder`](/slides/python-net/zh/aspose.slides/autoshape/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/autoshape/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/autoshape/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh/aspose.slides/autoshape/frame/) | 返回或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh/aspose.slides/autoshape/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线条属性的形状，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/autoshape/three_d_format/) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。<br/>            注意：对于某些没有 3D 属性的形状，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides/autoshape/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides/autoshape/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对于某些没有填充属性的形状，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/autoshape/hyperlink_click/) | 返回或设置鼠标单击时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/autoshape/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/autoshape/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh/aspose.slides/autoshape/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**。 |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/autoshape/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回 Z 顺序最靠后的形状，<br/>            Shapes[Shapes.Count - 1] 返回 Z 顺序最靠前的形状。<br/>            只读 **int**。 |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/autoshape/connection_site_count/) | 返回形状上连接点的数量。<br/>            只读 **int**。 |
| [`rotation`](/slides/python-net/zh/aspose.slides/autoshape/rotation/) | 返回或设置指定形状围绕 Z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**。 |
| [`x`](/slides/python-net/zh/aspose.slides/autoshape/x/) | 获取或设置形状左上角的 X 坐标，单位为点。<br/>            读写 **float**。 |
| [`y`](/slides/python-net/zh/aspose.slides/autoshape/y/) | 获取或设置形状左上角的 Y 坐标，单位为点。<br/>            读写 **float**。 |
| [`width`](/slides/python-net/zh/aspose.slides/autoshape/width/) | 获取或设置形状的宽度，单位为点。<br/>            读写 **float**。 |
| [`height`](/slides/python-net/zh/aspose.slides/autoshape/height/) | 获取或设置形状的高度，单位为点。<br/>            读写 **float**。 |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/autoshape/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh/aspose.slides/autoshape/unique_id/) | 返回内部的、面向演示文稿的标识符，供加载项或其他代码使用。<br/>            由于该值可能被用户或程序重新分配，不能将其视为持久唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/autoshape/office_interop_shape_id/) | 返回在幻灯片范围内唯一的标识符，在形状生命周期内保持不变，便于 PowerPoint 或互操作代码从文档任何位置可靠引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/autoshape/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            读写 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/autoshape/alternative_text_title/) | 返回或设置与形状关联的替代文本标题。<br/>            读写 **str**。 |
| [`name`](/slides/python-net/zh/aspose.slides/autoshape/name/) | 返回或设置形状的名称。<br/>            必须不为 None。如有需要请使用空字符串。<br/>            读写 **str**。 |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/autoshape/is_decorative/) | 获取或设置“标记为装饰性”选项。<br/>            读写 **bool**。 |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/autoshape/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IAutoShapeLock`](/slides/python-net/zh/aspose.slides/iautoshapelock)。 |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/autoshape/is_grouped/) | 确定形状是否已分组。<br/>            只读 **bool**。 |
| [`parent_group`](/slides/python-net/zh/aspose.slides/autoshape/parent_group/) | 如果形状已分组，返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/autoshape/slide/) | 返回形状所在的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh/aspose.slides/autoshape/presentation/) | 返回父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`shape_style`](/slides/python-net/zh/aspose.slides/autoshape/shape_style/) | 返回形状的样式对象。<br/>            只读 [`IShapeStyle`](/slides/python-net/zh/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/zh/aspose.slides/autoshape/shape_type/) | 返回或设置几何预设类型。<br/>            注意：值改变时，所有调节值将重置为默认值。<br/>            读写 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/zh/aspose.slides/autoshape/adjustments/) | 返回形状的调节值集合。<br/>            只读 [`IAdjustValueCollection`](/slides/python-net/zh/aspose.slides/iadjustvaluecollection)。 |
| [`auto_shape_lock`](/slides/python-net/zh/aspose.slides/autoshape/auto_shape_lock/) | 返回自动形状的锁定状态。<br/>            只读 [`IAutoShapeLock`](/slides/python-net/zh/aspose.slides/iautoshapelock)。 |
| [`text_frame`](/slides/python-net/zh/aspose.slides/autoshape/text_frame/) | 返回 AutoShape 的 TextFrame 对象。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe)。 |
| [`use_background_fill`](/slides/python-net/zh/aspose.slides/autoshape/use_background_fill/) | 确定此自动形状是否应使用幻灯片的背景填充，而不是样式或填充格式指定的填充。<br/>            读写 **bool**。 |
| [`is_text_box`](/slides/python-net/zh/aspose.slides/autoshape/is_text_box/) | 指定形状是否为文本框。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/autoshape/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/autoshape/write_as_svg/#iorawiobase) | 将形状内容另存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将形状内容另存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/autoshape/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/autoshape/add_placeholder/#iplaceholder) | 如果不存在占位符，则添加新占位符并将占位符属性设置为指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/autoshape/get_base_placeholder/#) | 返回基本占位符形状（当前形状继承自的布局或母版幻灯片中的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/autoshape/get_visual_bounds/#) | 获取从渲染内容计算得到的形状可视边界。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh/aspose.slides/autoshape/get_geometry_paths/#) | 返回几何形状路径的副本。坐标相对于形状左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | 根据 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于形状左上角。<br/>            将形状类型（[`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)）更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | 根据 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 数组更新形状几何。坐标必须相对于形状左上角。<br/>            将形状类型（[`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)）更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh/aspose.slides/autoshape/create_shape_elements/#) | 创建并返回形状元素数组。 |
| [`add_text_frame(self, text)`](/slides/python-net/zh/aspose.slides/autoshape/add_text_frame/#str) | 向形状添加新的 TextFrame。<br/>            如果形状已经有 TextFrame，则仅更改其文本。 |


### 另请参见
* class [`AutoShape`](/slides/python-net/zh/aspose.slides/autoshape)
* class [`GeometryShape`](/slides/python-net/zh/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)