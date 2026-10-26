---
title: IGeometryShape class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/igeometryshape/
---
## IGeometryShape 类

表示所有几何形状的父类。

IGeometryShape 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`shape_style`](/slides/python-net/zh/aspose.slides/igeometryshape/shape_style/) | 返回形状的样式对象。<br/>            只读 [`IShapeStyle`](/slides/python-net/zh/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/zh/aspose.slides/igeometryshape/shape_type/) | 返回或设置几何预设类型。<br/>            注意：值更改时，所有调整值将重置为默认值。<br/>            读写 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/zh/aspose.slides/igeometryshape/adjustments/) | 返回形状的调整值集合。<br/>            只读 [`IAdjustValueCollection`](/slides/python-net/zh/aspose.slides/iadjustvaluecollection)。 |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/zh/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/zh/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/zh/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/zh/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/zh/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/zh/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/zh/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/zh/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/zh/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/zh/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/zh/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/zh/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/zh/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/zh/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/zh/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/zh/aspose.slides/igeometryshape/get_geometry_paths/#) | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | 从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于左<br/>             上角的形状。<br/>             将形状的类型 ([`IGeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/igeometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | 从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 数组更新形状几何。坐标必须相对于左<br/>             上角的形状。<br/>             将形状的类型 ([`IGeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/igeometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh/aspose.slides/igeometryshape/create_shape_elements/#) | 创建并返回形状元素的数组。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)