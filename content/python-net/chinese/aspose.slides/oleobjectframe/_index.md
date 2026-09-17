---
title: OleObjectFrame class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/oleobjectframe/
---
## OleObjectFrame 类

表示幻灯片上的 OLE 对象。

**继承:**[`OleObjectFrame`](/slides/python-net/zh/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

OleObjectFrame 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/oleobjectframe/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**。 |
| [`placeholder`](/slides/python-net/zh/aspose.slides/oleobjectframe/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/zh/aspose.slides/oleobjectframe/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/oleobjectframe/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/zh/aspose.slides/oleobjectframe/frame/) | 返回或设置形状框架的属性。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/zh/aspose.slides/oleobjectframe/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对于某些没有线条属性的形状类型，可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/oleobjectframe/three_d_format/) | 返回形状的 ThreeDFormat 对象，该对象包含 3D 效果属性。<br/>            注意：对于某些没有 3D 属性的形状类型，可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/zh/aspose.slides/oleobjectframe/effect_format/) | 返回包含应用于形状的像素效果的 EffectFormat 对象。<br/>            注意：对于某些没有效果属性的形状类型，可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/zh/aspose.slides/oleobjectframe/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对于某些没有填充属性的形状类型，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/oleobjectframe/hyperlink_click/) | 返回或设置鼠标点击时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/oleobjectframe/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/zh/aspose.slides/oleobjectframe/hidden/) | 确定形状是否隐藏。<br/>            读写 **bool**。 |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/oleobjectframe/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回位于 Z 顺序最底部的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回位于 Z 顺序最前端的形状。<br/>            只读 **int**。 |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/oleobjectframe/connection_site_count/) | 返回形状的连接点数量。<br/>            只读 **int**。 |
| [`rotation`](/slides/python-net/zh/aspose.slides/oleobjectframe/rotation/) | 返回或设置指定形状绕 Z 轴旋转的角度（度数）。正值表示顺时针旋转，负值表示逆时针旋转。<br/>            读写 **float**。 |
| [`x`](/slides/python-net/zh/aspose.slides/oleobjectframe/x/) | 获取或设置形状左上角的 X 坐标，单位为点（points）。<br/>            读写 **float**。 |
| [`y`](/slides/python-net/zh/aspose.slides/oleobjectframe/y/) | 获取或设置形状左上角的 Y 坐标，单位为点（points）。<br/>            读写 **float**。 |
| [`width`](/slides/python-net/zh/aspose.slides/oleobjectframe/width/) | 获取或设置形状的宽度，单位为点（points）。<br/>            读写 **float**。 |
| [`height`](/slides/python-net/zh/aspose.slides/oleobjectframe/height/) | 获取或设置形状的高度，单位为点（points）。<br/>            读写 **float**。 |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/oleobjectframe/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/zh/aspose.slides/oleobjectframe/unique_id/) | 返回用于插件或其他代码的内部、演示文稿范围的标识符。<br/>            由于此值可能被用户或程序重新分配，因而不应视为持久的唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/oleobjectframe/office_interop_shape_id/) | 返回在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，并使 PowerPoint 或互操作代码能够从文档的任何位置可靠地引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/oleobjectframe/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            读写 **str**。 |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/oleobjectframe/alternative_text_title/) | 返回或设置与形状关联的替代文本标题。<br/>            读写 **str**。 |
| [`name`](/slides/python-net/zh/aspose.slides/oleobjectframe/name/) | 返回或设置形状的名称。<br/>            必须不为 None。如有需要请使用空字符串。<br/>            读写 **str**。 |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/oleobjectframe/is_decorative/) | 获取或设置“标记为装饰”选项<br/>            读写 **bool**。 |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/oleobjectframe/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/oleobjectframe/is_grouped/) | 确定形状是否已分组。<br/>            只读 **bool**。 |
| [`parent_group`](/slides/python-net/zh/aspose.slides/oleobjectframe/parent_group/) | 如果形状已分组，返回其父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/zh/aspose.slides/oleobjectframe/slide/) | 返回形状所在的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/zh/aspose.slides/oleobjectframe/presentation/) | 返回幻灯片所在的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides/oleobjectframe/graphical_object_lock/) | 返回形状的锁定状态。<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock)。 |
| [`substitute_picture_format`](/slides/python-net/zh/aspose.slides/oleobjectframe/substitute_picture_format/) | 返回 OleObject 图像填充属性对象。<br/>            只读 [`IPictureFillFormat`](/slides/python-net/zh/aspose.slides/ipicturefillformat)。 |
| [`substitute_picture_title`](/slides/python-net/zh/aspose.slides/oleobjectframe/substitute_picture_title/) | 返回或设置 OleObject 图标的标题。<br/>            读写 **str**。 |
| [`object_name`](/slides/python-net/zh/aspose.slides/oleobjectframe/object_name/) | 返回或设置对象的名称。<br/>            读写 **str**。 |
| [`object_prog_id`](/slides/python-net/zh/aspose.slides/oleobjectframe/object_prog_id/) | 返回对象的 ProgID。<br/>            只读 **str**。 |
| [`link_file_name`](/slides/python-net/zh/aspose.slides/oleobjectframe/link_file_name/) | 返回链接文件的完整路径。将使用短文件名。<br/>            只读 **str**。 |
| [`link_path_long`](/slides/python-net/zh/aspose.slides/oleobjectframe/link_path_long/) | 返回链接文件的完整路径。将使用长文件名。<br/>            读写 **str**。 |
| [`link_path_relative`](/slides/python-net/zh/aspose.slides/oleobjectframe/link_path_relative/) | 如果存在，则返回链接文件的相对路径；否则返回空字符串。<br/>            只读 **str**。 |
| [`embedded_file_label`](/slides/python-net/zh/aspose.slides/oleobjectframe/embedded_file_label/) | 返回嵌入式 OLE 对象的文件名 |
| [`embedded_file_name`](/slides/python-net/zh/aspose.slides/oleobjectframe/embedded_file_name/) | 返回嵌入式 OLE 对象的路径 |
| [`embedded_data`](/slides/python-net/zh/aspose.slides/oleobjectframe/embedded_data/) | 获取或设置 OLE 嵌入数据的信息。<br/>            读写 [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo)。 |
| [`is_object_icon`](/slides/python-net/zh/aspose.slides/oleobjectframe/is_object_icon/) | 确定对象是否以图标形式可见。<br/>            读写 **bool**。 |
| [`is_object_link`](/slides/python-net/zh/aspose.slides/oleobjectframe/is_object_link/) | 确定对象是否链接到外部文件。<br/>            只读 **bool**。 |
| [`update_automatic`](/slides/python-net/zh/aspose.slides/oleobjectframe/update_automatic/) | 确定在打开或打印演示文稿时，链接的嵌入对象是否自动更新。<br/>            读写 **bool**。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/oleobjectframe/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | 将形状的内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将形状的内容保存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/oleobjectframe/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | 如果不存在，则添加新占位符并将占位符属性设置为指定的占位符。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/oleobjectframe/get_base_placeholder/#) | 返回基本占位符形状（即当前形状继承自的布局和/或母版幻灯片中的形状）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/oleobjectframe/get_visual_bounds/#) | 获取根据渲染内容计算的形状可视边界。 |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/zh/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | 设置 OLE 嵌入数据的信息。<br/>            <br/>            此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设为 false，表示 OLE 对象已嵌入。 |

### 另见
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`OleObjectFrame`](/slides/python-net/zh/aspose.slides/oleobjectframe)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)