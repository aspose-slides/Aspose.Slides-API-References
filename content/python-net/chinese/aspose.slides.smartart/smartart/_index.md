---
title: SmartArt class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/smartart/
---
## SmartArt 类

表示一个 SmartArt 图表

**Inheritance:**[`SmartArt`](/slides/python-net/zh/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

SmartArt 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides.smartart/smartart/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides.smartart/smartart/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides.smartart/smartart/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides.smartart/smartart/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides.smartart/smartart/frame/) | 返回或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides.smartart/smartart/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线属性的形状，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides.smartart/smartart/three_d_format/) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。<br/>            注意：对于某些没有 3D 属性的形状，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides.smartart/smartart/effect_format/) | 返回包含对形状应用的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides.smartart/smartart/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对于某些没有填充属性的形状，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides.smartart/smartart/hyperlink_click/) | 返回或设置鼠标单击时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides.smartart/smartart/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh/aspose.slides.smartart/smartart/hidden/) | 确定形状是否被隐藏。<br/>            读写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides.smartart/smartart/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回 Z 顺序最靠后的形状，<br/>            Shapes[Shapes.Count - 1] 返回 Z 顺序最靠前的形状。<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides.smartart/smartart/connection_site_count/) | 返回形状上的连接点数量。<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides.smartart/smartart/rotation/) | 返回或设置形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            读写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides.smartart/smartart/x/) | 获取或设置形状左上角的 X 坐标，单位为点。<br/>            读写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides.smartart/smartart/y/) | 获取或设置形状左上角的 Y 坐标，单位为点。<br/>            读写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides.smartart/smartart/width/) | 获取或设置形状的宽度，单位为点。<br/>            读写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides.smartart/smartart/height/) | 获取或设置形状的高度，单位为点。<br/>            读写 **float**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides.smartart/smartart/black_white_mode/) | 指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh/aspose.slides.smartart/smartart/unique_id/) | 返回供插件或其他代码使用的内部、演示范围标识符。<br/>            因为此值可能被用户或程序重新分配，不能视为持久唯一键。<br/>            只读 **int**.<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides.smartart/smartart/office_interop_shape_id/) | 返回在幻灯片范围内唯一的标识符，在形状生命周期内保持不变，PowerPoint 或互操作代码可可靠地从文档任意位置引用该形状。<br/>            只读 **int**.<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh/aspose.slides.smartart/smartart/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            读写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides.smartart/smartart/alternative_text_title/) | 返回或设置与形状关联的替代文本标题。<br/>            读写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides.smartart/smartart/name/) | 返回或设置形状的名称。<br/>            必须非 None。必要时使用空字符串。<br/>            读写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides.smartart/smartart/is_decorative/) | 获取或设置“标记为装饰性”选项<br/>            读写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides.smartart/smartart/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides.smartart/smartart/is_grouped/) | 确定形状是否被分组。<br/>            只读 **bool**. |
| [`parent_group`](/slides/python-net/zh/aspose.slides.smartart/smartart/parent_group/) | 如果形状被分组，返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides.smartart/smartart/slide/) | 返回形状所属的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh/aspose.slides.smartart/smartart/presentation/) | 返回幻灯片所属的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides.smartart/smartart/graphical_object_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/zh/aspose.slides.smartart/smartart/all_nodes/) | 返回 SmartArt 对象中所有节点的集合。<br/>            只读 [`ISmartArtNodeCollection`](/slides/python-net/zh/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/zh/aspose.slides.smartart/smartart/nodes/) | 返回 SmartArt 对象中根节点的集合。<br/>            只读 [`ISmartArtNodeCollection`](/slides/python-net/zh/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/zh/aspose.slides.smartart/smartart/layout/) | 返回或设置 SmartArt 对象的布局。<br/>            读写 [`SmartArtLayoutType`](/slides/python-net/zh/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/zh/aspose.slides.smartart/smartart/quick_style/) | 返回或设置 SmartArt 对象的快速样式。<br/>            读写 [`SmartArtQuickStyleType`](/slides/python-net/zh/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/zh/aspose.slides.smartart/smartart/color_style/) | 返回或设置 SmartArt 对象的颜色样式。<br/>            读写 [`SmartArtColorType`](/slides/python-net/zh/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/zh/aspose.slides.smartart/smartart/is_reversed/) | 返回或设置 SmartArt 图表的方向状态（从左到右 LTR 或从右到左 RTL），如果图表支持反转。<br/>            读写 **bool**. |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides.smartart/smartart/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | 将形状内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将形状内容保存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides.smartart/smartart/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | 如果不存在则添加新的占位符，并将占位符属性设置为指定的属性。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides.smartart/smartart/get_base_placeholder/#) | 返回基本占位符形状（从布局和/或母版幻灯片中继承的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides.smartart/smartart/get_visual_bounds/#) | 获取根据渲染内容计算的形状可视边界。 |

### 另见
* class [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* class [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* class [`SmartArt`](/slides/python-net/zh/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)