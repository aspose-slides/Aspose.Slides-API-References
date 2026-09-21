---
title: IGeometryShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/igeometryshape/
---
## IGeometryShape คลาส

Represents the parent class for all geometric shapes.

The IGeometryShape type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`shape_style`](/slides/python-net/th/aspose.slides/igeometryshape/shape_style/) | Returns shape's style object.<br/>อ่านอย่างเดียว [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/igeometryshape/shape_type/) | Returns or sets the geometry preset type.<br/>หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับทั้งหมดจะกลับเป็นค่าดีฟอลต์.<br/>อ่าน/เขียน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/igeometryshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>อ่านอย่างเดียว [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/th/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/th/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/th/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/th/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/th/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/th/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/th/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/th/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/th/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/th/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/th/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/th/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/th/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/th/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/th/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/th/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/igeometryshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>top corner of the shape.<br/>Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/th/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>top corner of the shape.<br/>Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/th/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/igeometryshape/create_shape_elements/#) | Creates and returns array of shape's elements. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)