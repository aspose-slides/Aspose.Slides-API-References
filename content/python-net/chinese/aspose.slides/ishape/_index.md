---
title: IShape class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishape/
---
## IShape 类

表示幻灯片上的形状。

IShape 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/ishape/is_text_holder/) | 确定形状是否为 TextHolder。<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides/ishape/placeholder/) | 返回形状的占位符。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/ishape/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/ishape/raw_frame/) | 返回或设置原始形状框的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides/ishape/frame/) | 返回或设置形状框的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides/ishape/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/ishape/three_d_format/) | 返回包含形状线条格式属性的 ThreeDFormat 对象。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/ishape/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/ishape/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/zh/aspose.slides/ishape/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/ishape/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回位于 Z 顺序最后面的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回位于 Z 顺序最前面的形状。<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/ishape/connection_site_count/) | 返回形状上的连接点数量。<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides/ishape/rotation/) | 返回或设置指定形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides/ishape/x/) | 获取或设置形状左上角的 X 坐标（单位：点）。<br/>            读写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/ishape/y/) | 获取或设置形状左上角的 Y 坐标（单位：点）。<br/>            读写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/ishape/width/) | 获取或设置形状的宽度（单位：点）。<br/>            读写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/ishape/height/) | 获取或设置形状的高度（单位：点）。<br/>            读写 **float**. |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/ishape/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            读写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/ishape/alternative_text_title/) | 返回或设置与形状关联的替代文本标题。<br/>            读写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides/ishape/name/) | 返回或设置形状的名称。<br/>            读写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/ishape/is_decorative/) | 获取或设置 “标记为装饰性” 选项<br/>            读写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/ishape/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IBaseShapeLock`](/slides/python-net/zh/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/zh/aspose.slides/ishape/unique_id/) | 返回供插件或其他代码使用的内部、演示范围标识符。<br/>            由于此值可能被用户或程序重新分配，不能视为持久唯一键。<br/>            只读 **int**.<br/>            另见 [`IShape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/ishape/office_interop_shape_id/) | 返回在幻灯片范围内唯一且在形状生命周期内保持不变的标识符，PowerPoint 或互操作代码可可靠地从文档任何位置引用该形状。<br/>            只读 **int**.<br/>            另见 [`IShape.unique_id`](/slides/python-net/zh/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/ishape/is_grouped/) | 确定形状是否被分组。<br/>            只读 **bool**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/ishape/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/zh/aspose.slides/ishape/parent_group/) | 如果形状已分组，则返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/ishape/hyperlink_manager/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/ishape/get_image/#) | 返回形状缩略图。<br/>            ShapeThumbnailBounds.Shape 形状缩略图边界类型默认使用. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/ishape/write_as_svg/#iorawiobase) | 将 Shape 内容另存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将 Shape 内容另存为 SVG 文件。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/ishape/add_placeholder/#iplaceholder) | 如果不存在，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/ishape/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/ishape/get_base_placeholder/#) | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从其继承）。<br/>            如果当前形状未继承，则返回 None。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)