---
title: IAutoShape class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/iautoshape/
---
## IAutoShape lớp

Đại diện cho một AutoShape.

Kiểu IAutoShape cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/iautoshape/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IAutoShapeLock`](/slides/python-net/vi/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/vi/aspose.slides/iautoshape/auto_shape_lock/) | Trả về các khóa của AutoShape.<br/>            Chỉ đọc [`IAutoShapeLock`](/slides/python-net/vi/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/vi/aspose.slides/iautoshape/text_frame/) | Trả về đối tượng TextFrame cho AutoShape.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/vi/aspose.slides/iautoshape/use_background_fill/) | Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi kiểu hoặc định dạng tô màu hay không.<br/>            Đọc/ghi **bool**. |
| [`is_text_box`](/slides/python-net/vi/aspose.slides/iautoshape/is_text_box/) | Xác định xem hình dạng có phải là một hộp văn bản hay không. |
| [`shape_style`](/slides/python-net/vi/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/vi/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/vi/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/vi/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/vi/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/vi/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/vi/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/vi/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/vi/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/vi/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/vi/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/vi/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/vi/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/vi/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/vi/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/vi/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/vi/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/vi/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/vi/aspose.slides/iautoshape/add_text_frame/#str) | Thêm một TextFrame mới vào hình dạng.<br/>            Nếu hình dạng đã có TextFrame thì chỉ thay đổi văn bản của nó. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)