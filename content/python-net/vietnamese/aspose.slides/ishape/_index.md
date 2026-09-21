---
title: IShape class
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/ishape/
---
## IShape lớp

Biểu diễn một hình dạng trên slide.

Kiểu IShape cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/ishape/is_text_holder/) | Xác định liệu hình dạng có phải là TextHolder hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/ishape/placeholder/) | Trả về placeholder cho một hình dạng.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/ishape/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/ishape/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/ishape/frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/ishape/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/ishape/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/ishape/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/ishape/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/vi/aspose.slides/ishape/hidden/) | Xác định liệu hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/ishape/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau nhất của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước nhất của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/ishape/connection_site_count/) | Trả về số lượng vị trí kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/ishape/rotation/) | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/ishape/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/ishape/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/ishape/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/ishape/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/ishape/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/ishape/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/ishape/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/ishape/is_decorative/) | Lấy hoặc đặt tùy chọn ‘Mark as decorative’<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/ishape/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IBaseShapeLock`](/slides/python-net/vi/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/ishape/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dự định dùng cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nó không nên được coi là khóa duy nhất giữ lâu dài.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`IShape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/ishape/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, giữ cố định trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`IShape.unique_id`](/slides/python-net/vi/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/ishape/is_grouped/) | Xác định liệu hình dạng có được nhóm không.<br/>            Chỉ đọc **bool**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/ishape/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/vi/aspose.slides/ishape/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/ishape/hyperlink_manager/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/ishape/get_image/#) | Trả về hình thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/ishape/write_as_svg/#iorawiobase) | Lưu nội dung của Shape thành tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape thành tệp SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/ishape/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder thành một placeholder đã chỉ định. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/ishape/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/ishape/get_base_placeholder/#) | Trả về một hình placeholder cơ bản (hình từ bố cục và/hoặc slide master mà hình hiện tại kế thừa).<br/>            Trả về None nếu hình hiện tại không được kế thừa. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)