---
title: SectionZoomFrame class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame 类

Represents a Section Zoom object in a slide.

**Inheritance:**[`SectionZoomFrame`](/slides/python-net/zh/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/zh/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

The SectionZoomFrame type exposes the following members:

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/sectionzoomframe/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides/sectionzoomframe/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/sectionzoomframe/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/sectionzoomframe/raw_frame/) | 获取或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides/sectionzoomframe/frame/) | 获取或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides/sectionzoomframe/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线条属性的形状类型，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/sectionzoomframe/three_d_format/) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。<br/>            注意：对于某些没有 3D 属性的形状类型，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/sectionzoomframe/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状类型，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/sectionzoomframe/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对于某些没有填充属性的形状类型，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/sectionzoomframe/hyperlink_click/) | 获取或设置鼠标点击时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | 获取或设置鼠标悬停时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/sectionzoomframe/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh/aspose.slides/sectionzoomframe/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/sectionzoomframe/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回位于 Z 顺序后面的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回位于 Z 顺序前面的形状。<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/sectionzoomframe/connection_site_count/) | 返回形状的连接点数量。<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides/sectionzoomframe/rotation/) | 获取或设置指定形状绕 Z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides/sectionzoomframe/x/) | 获取或设置形状左上角的 X 坐标（以点为单位）。<br/>            读写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/sectionzoomframe/y/) | 获取或设置形状左上角的 Y 坐标（以点为单位）。<br/>            读写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/sectionzoomframe/width/) | 获取或设置形状的宽度（以点为单位）。<br/>            读写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/sectionzoomframe/height/) | 获取或设置形状的高度（以点为单位）。<br/>            读写 **float**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/sectionzoomframe/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh/aspose.slides/sectionzoomframe/unique_id/) | 返回用于插件或其他代码的内部演示范围标识符。<br/>            因为此值可能被用户或程序重新分配，不能视为持久唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/sectionzoomframe/office_interop_shape_id/) | 返回一个在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，允许 PowerPoint 或互操作代码在文档的任何位置可靠地引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/sectionzoomframe/alternative_text/) | 获取或设置与形状关联的替代文字。<br/>            读写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/sectionzoomframe/alternative_text_title/) | 获取或设置与形状关联的替代文字标题。<br/>            读写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides/sectionzoomframe/name/) | 获取或设置形状的名称。<br/>            必须非 None；如有需要可使用空字符串。<br/>            读写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/sectionzoomframe/is_decorative/) | 获取或设置“标记为装饰”选项<br/>            读写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/sectionzoomframe/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/sectionzoomframe/is_grouped/) | 确定形状是否被分组。<br/>            只读 **bool**. |
| [`parent_group`](/slides/python-net/zh/aspose.slides/sectionzoomframe/parent_group/) | 如果形状被分组，则返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides/sectionzoomframe/slide/) | 返回形状的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh/aspose.slides/sectionzoomframe/presentation/) | 返回幻灯片的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides/sectionzoomframe/graphical_object_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/zh/aspose.slides/sectionzoomframe/image_type/) | 获取或设置缩放对象的图像类型。<br/>            读写 [`ZoomImageType`](/slides/python-net/zh/aspose.slides/zoomimagetype)。<br/>            默认值：Preview |
| [`return_to_parent`](/slides/python-net/zh/aspose.slides/sectionzoomframe/return_to_parent/) | 获取或设置幻灯片放映中的导航行为。<br/>            读写 **bool**。<br/>            默认值：false |
| [`show_background`](/slides/python-net/zh/aspose.slides/sectionzoomframe/show_background/) | 获取或设置指定 Zoom 是否使用目标幻灯片背景的值。<br/>            读写 **bool**。<br/>            默认值：true |
| [`zoom_image`](/slides/python-net/zh/aspose.slides/sectionzoomframe/zoom_image/) | 获取或设置缩放对象的图像。<br/>            读写 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/zh/aspose.slides/sectionzoomframe/transition_duration/) | 获取或设置 Zoom 与幻灯片之间过渡的持续时间。<br/>            读写 **float**。<br/>            默认值：1.0f |
| [`target_section`](/slides/python-net/zh/aspose.slides/sectionzoomframe/target_section/) | 获取或设置 Section Zoom 对象链接的章节对象。<br/>            读写 [`ISection`](/slides/python-net/zh/aspose.slides/isection). |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | 将形状内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将形状内容保存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | 如果不存在则添加一个新占位符，并将占位符属性设置为指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/get_base_placeholder/#) | 返回基本占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/sectionzoomframe/get_visual_bounds/#) | 获取根据渲染内容计算的形状可视边界。 |

### 另见
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`SectionZoomFrame`](/slides/python-net/zh/aspose.slides/sectionzoomframe)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 类 [`ZoomObject`](/slides/python-net/zh/aspose.slides/zoomobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)