---
title: Ink class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ink/ink/
---
## Ink 类

Represents an ink object on a slide.

**继承:**[`Ink`](/slides/python-net/zh/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

Ink 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides.ink/ink/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**。 |
| [`placeholder`](/slides/python-net/zh/aspose.slides.ink/ink/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides.ink/ink/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh/aspose.slides.ink/ink/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh/aspose.slides.ink/ink/frame/) | 返回或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh/aspose.slides.ink/ink/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对某些没有线条属性的形状可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh/aspose.slides.ink/ink/three_d_format/) | 返回形状的 ThreeDFormat 对象，该对象包含 3D 效果属性。<br/>            注意：对某些没有 3D 属性的形状可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides.ink/ink/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对某些没有 effect 属性的形状可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides.ink/ink/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对某些没有 fill 属性的形状可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides.ink/ink/hyperlink_click/) | 返回或设置用于鼠标点击的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides.ink/ink/hyperlink_mouse_over/) | 返回或设置用于鼠标悬停的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides.ink/ink/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh/aspose.slides.ink/ink/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**。 |
| [`z_order_position`](/slides/python-net/zh/aspose.slides.ink/ink/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回 Z 顺序最底部的形状，<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            只读 **int**。 |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides.ink/ink/connection_site_count/) | 返回形状的连接点数量。<br/>            只读 **int**。 |
| [`rotation`](/slides/python-net/zh/aspose.slides.ink/ink/rotation/) | 返回或设置指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**。 |
| [`x`](/slides/python-net/zh/aspose.slides.ink/ink/x/) | 获取或设置形状左上角的 x 坐标，单位为点。<br/>            读写 **float**。 |
| [`y`](/slides/python-net/zh/aspose.slides.ink/ink/y/) | 获取或设置形状左上角的 y 坐标，单位为点。<br/>            读写 **float**。 |
| [`width`](/slides/python-net/zh/aspose.slides.ink/ink/width/) | 获取或设置形状的宽度，单位为点。<br/>            读写 **float**。 |
| [`height`](/slides/python-net/zh/aspose.slides.ink/ink/height/) | 获取或设置形状的高度，单位为点。<br/>            读写 **float**。 |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides.ink/ink/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh/aspose.slides.ink/ink/unique_id/) | 返回内部的、针对演示文稿范围的标识符，供加载项或其他代码使用。<br/>            由于此值可能被用户或程序重新分配，不能将其视为持久唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides.ink/ink/office_interop_shape_id/) | 返回在幻灯片范围内唯一的标识符，在形状生命周期内保持不变，并使 PowerPoint 或互操作代码能够可靠地从文档任何位置引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh/aspose.slides.ink/ink/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            读写 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides.ink/ink/alternative_text_title/) | 返回或设置与形状关联的替代文本的标题。<br/>            读写 **str**。 |
| [`name`](/slides/python-net/zh/aspose.slides.ink/ink/name/) | 返回或设置形状的名称。<br/>            必须不为 None。如有需要请使用空字符串。<br/>            读写 **str**。 |
| [`is_decorative`](/slides/python-net/zh/aspose.slides.ink/ink/is_decorative/) | 获取或设置“标记为装饰性”选项。<br/>            读写 **bool**。 |
| [`shape_lock`](/slides/python-net/zh/aspose.slides.ink/ink/shape_lock/) | 返回形状的锁。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh/aspose.slides.ink/ink/is_grouped/) | 确定形状是否为组合。<br/>            只读 **bool**。 |
| [`parent_group`](/slides/python-net/zh/aspose.slides.ink/ink/parent_group/) | 如果形状为组合，则返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh/aspose.slides.ink/ink/slide/) | 返回形状的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh/aspose.slides.ink/ink/presentation/) | 返回幻灯片的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides.ink/ink/graphical_object_lock/) | 返回形状的锁。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock)。 |
| [`traces`](/slides/python-net/zh/aspose.slides.ink/ink/traces/) | 获取 IInk 元素 [`IInkTrace`](/slides/python-net/zh/aspose.slides.ink/iinktrace) 中包含的所有痕迹。<br/>            只读。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides.ink/ink/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | 将 Shape 内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将 Shape 内容保存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides.ink/ink/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | 如果不存在，则添加新占位符并将占位符属性设置为指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides.ink/ink/get_base_placeholder/#) | 返回基本占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides.ink/ink/get_visual_bounds/#) | 获取根据渲染内容计算的形状可视边界。 |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/zh/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | 将图像注册到用于模拟墨水笔刷视觉效果的自定义图像集合中。<br/>            当使用特定的 [`InkEffectType`](/slides/python-net/zh/aspose.slides.ink/inkeffecttype) 值渲染墨水时（例如 Galaxy、Rainbow 等），会使用这些图像。通过提供自己的图像，您可以控制每种墨水效果的显示方式。 |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/zh/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | 从用于模拟墨水笔刷视觉效果的自定义图像集合中注销先前通过 **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide** 注册的图像。 |

### 另见
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`Ink`](/slides/python-net/zh/aspose.slides.ink/ink)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 模块 [`aspose.slides.ink`](/slides/python-net/zh/aspose.slides.ink)
* 库 [`Aspose.Slides`](/slides/python-net)