---
title: IGeometryShape class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/igeometryshape/
---
## IGeometryShape lớp

Đại diện cho lớp cha của tất cả các hình dạng hình học.

Kiểu IGeometryShape cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/vi/aspose.slides/igeometryshape/shape_style/) | Trả về đối tượng kiểu dáng của hình.<br/>            Read-only [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides/igeometryshape/shape_type/) | Trả về hoặc đặt loại mẫu hình học.<br/>            Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định.<br/>            Read/write [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides/igeometryshape/adjustments/) | Trả về một tập hợp các giá trị điều chỉnh của hình.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/vi/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/vi/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/vi/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/vi/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/vi/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/vi/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/vi/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/vi/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/vi/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/vi/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/vi/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/vi/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/vi/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/vi/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/vi/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/igeometryshape/get_geometry_paths/#) | Trả về bản sao của đường dẫn của hình dạng hình học. Tọa độ tương đối so với góc trái trên của hình dạng. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Cập nhật hình học hình dạng từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối so với góc trái<br/>             trên của hình dạng.<br/>             Thay đổi loại của hình dạng ([`IGeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/igeometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Cập nhật hình học hình dạng từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối so với góc trái<br/>             trên của hình dạng.<br/>             Thay đổi loại của hình dạng ([`IGeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/igeometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/igeometryshape/create_shape_elements/#) | Tạo và trả về mảng các phần tử của hình dạng. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/igeometryshape/get_base_placeholder/#) |  |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)