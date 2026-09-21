---
title: IConnector class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iconnector/
---
## IConnector lớp

Biểu thị một connector.

Kiểu IConnector cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/iconnector/shape_lock/) | Returns shape's locks.<br/>            Chỉ đọc [`IConnectorLock`](/slides/python-net/vi/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/vi/aspose.slides/iconnector/connector_lock/) | Returns Connector's locks.<br/>            Chỉ đọc [`IConnectorLock`](/slides/python-net/vi/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/vi/aspose.slides/iconnector/start_shape_connected_to/) | Trả về hoặc đặt hình để gắn đầu của connector.<br/>            Đọc/ghi [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/vi/aspose.slides/iconnector/end_shape_connected_to/) | Trả về hoặc đặt hình để gắn cuối của connector.<br/>            Đọc/ghi [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/vi/aspose.slides/iconnector/start_shape_connection_site_index/) | Trả về hoặc đặt chỉ mục của site kết nối cho hình bắt đầu.<br/>            Đọc/ghi **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/vi/aspose.slides/iconnector/end_shape_connection_site_index/) | Trả về hoặc đặt chỉ mục của site kết nối cho hình kết thúc.<br/>            Đọc/ghi **int**. |
| [`shape_style`](/slides/python-net/vi/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/vi/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/vi/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/vi/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/vi/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/vi/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/vi/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/vi/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/vi/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/vi/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/vi/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/vi/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/vi/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/vi/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/vi/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/vi/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/vi/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/vi/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/iconnector/hyperlink_manager/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/vi/aspose.slides/iconnector/reroute/#) | Định tuyến lại connector sao cho nó lấy đường ngắn nhất có thể giữa các hình mà nó kết nối. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/iconnector/get_base_placeholder/#) |  |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)