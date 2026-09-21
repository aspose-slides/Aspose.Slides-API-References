---
title: Shape class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shape/
---
## Lớp Shape

Đại diện cho một hình dạng trên slide.

Kiểu Shape cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/shape/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/shape/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/shape/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/shape/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/shape/frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/shape/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/shape/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/shape/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/shape/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/shape/hyperlink_click/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/shape/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/shape/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/shape/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/shape/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau nhất trong thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước nhất trong thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/shape/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/shape/rotation/) | Trả về hoặc đặt số độ mà hình dạng được xoay quanh trục z.<br/>            Giá trị dương biểu thị xoay theo chiều kim đồng hồ; giá trị âm biểu thị xoay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/shape/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/shape/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/shape/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/shape/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/shape/black_white_mode/) | Thuộc tính xác định cách một hình dạng sẽ hiển thị trong chế độ hiển thị đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id/) | Trả về định danh nội bộ, phạm vi của bản trình chiếu, dự định dùng cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nên không được coi là khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id/) | Trả về định danh duy nhất phạm vi slide, vẫn không đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/shape/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/shape/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/shape/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Phải không phải None. Sử dụng giá trị chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/shape/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/shape/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IBaseShapeLock`](/slides/python-net/vi/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/shape/is_grouped/) | Xác định xem hình dạng có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/shape/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Ngược lại trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/shape/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/shape/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/shape/get_image/#) | Trả về ảnh thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho vùng biên độ ảnh thu nhỏ của hình dạng. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/shape/write_as_svg/#iorawiobase) | Lưu nội dung của Shape thành tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape thành tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/shape/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/shape/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và đặt thuộc tính placeholder thành một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/shape/get_base_placeholder/#) | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide mẫu mà hình dạng hiện tại kế thừa).<br/>            Trả về None nếu hình dạng hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/shape/get_visual_bounds/#) | Lấy vùng biên giới trực quan của hình dạng được tính toán từ nội dung đã render. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)