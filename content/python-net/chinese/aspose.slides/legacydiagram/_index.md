---
title: LegacyDiagram class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/legacydiagram/
---
## LegacyDiagram 类

表示一个传统图表对象。

**继承:**[`LegacyDiagram`](/slides/python-net/zh/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

LegacyDiagram 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/legacydiagram/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides/legacydiagram/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/legacydiagram/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/legacydiagram/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides/legacydiagram/frame/) | 返回或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides/legacydiagram/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线条属性的形状类型，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/legacydiagram/three_d_format/) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。<br/>            注意：对于某些没有 3D 属性的形状类型，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/legacydiagram/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状类型，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/legacydiagram/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对于某些没有填充属性的形状类型，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/legacydiagram/hyperlink_click/) | 返回或设置鼠标点击时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/legacydiagram/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/legacydiagram/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh/aspose.slides/legacydiagram/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/legacydiagram/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回位于 Z 顺序最底部的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回位于 Z 顺序最前端的形状。<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/legacydiagram/connection_site_count/) | 返回形状的连接点数量。<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides/legacydiagram/rotation/) | 返回或设置指定形状绕 Z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides/legacydiagram/x/) | 获取或设置形状左上角的 X 坐标，单位为点。<br/>            读写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/legacydiagram/y/) | 获取或设置形状左上角的 Y 坐标，单位为点。<br/>            读写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/legacydiagram/width/) | 获取或设置形状的宽度，单位为点。<br/>            读写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/legacydiagram/height/) | 获取或设置形状的高度，单位为点。<br/>            读写 **float**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/legacydiagram/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh/aspose.slides/legacydiagram/unique_id/) | 返回内部的、在演示文稿范围内的标识符，供插件或其他代码使用。<br/>            由于该值可以被用户或程序重新分配，不能将其视为持久的唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/legacydiagram/office_interop_shape_id/) | 返回在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，允许 PowerPoint 或互操作代码在文档任意位置可靠地引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/legacydiagram/alternative_text/) | 返回或设置与形状关联的替代文字。<br/>            读写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/legacydiagram/alternative_text_title/) | 返回或设置与形状关联的替代文字标题。<br/>            读写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides/legacydiagram/name/) | 返回或设置形状的名称。<br/>            必须不为 None。如有需要可使用空字符串。<br/>            读写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/legacydiagram/is_decorative/) | 获取或设置“标记为装饰性”选项<br/>            读写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/legacydiagram/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/legacydiagram/is_grouped/) | 确定形状是否被分组。<br/>            只读 **bool**. |
| [`parent_group`](/slides/python-net/zh/aspose.slides/legacydiagram/parent_group/) | 如果形状被分组，返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides/legacydiagram/slide/) | 返回形状的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh/aspose.slides/legacydiagram/presentation/) | 返回幻灯片的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides/legacydiagram/graphical_object_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/legacydiagram/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | 将 Shape 内容另存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将 Shape 内容另存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/legacydiagram/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | 如果不存在占位符，则添加一个新的占位符并将占位符属性设置为指定的。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/legacydiagram/get_base_placeholder/#) | 返回基本占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/legacydiagram/get_visual_bounds/#) | 获取根据渲染内容计算的形状可视边界。 |
| [`convert_to_smart_art(self)`](/slides/python-net/zh/aspose.slides/legacydiagram/convert_to_smart_art/#) | 将传统图表转换为可编辑的 SmartArt 对象。<br/>            创建的 SmartArt 对象在相同位置添加到父组形状中。 |
| [`convert_to_group_shape(self)`](/slides/python-net/zh/aspose.slides/legacydiagram/convert_to_group_shape/#) | 将传统图表转换为可编辑的组形状。<br/>            创建的 GroupShape 对象在相同位置添加到父组形状中。 |

### 另见
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`LegacyDiagram`](/slides/python-net/zh/aspose.slides/legacydiagram)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)