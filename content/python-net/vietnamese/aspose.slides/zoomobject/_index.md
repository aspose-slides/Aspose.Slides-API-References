---
title: ZoomObject class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/zoomobject/
---
## ZoomObject lớp

Biểu diễn một đối tượng Zoom trong một slide.

**Kế thừa:**[`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu ZoomObject cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/zoomobject/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/zoomobject/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/zoomobject/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/zoomobject/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/zoomobject/frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/zoomobject/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/zoomobject/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/zoomobject/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/zoomobject/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/zoomobject/hyperlink_click/) | Trả về hoặc đặt liên kết được định nghĩa cho lần nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/zoomobject/hyperlink_mouse_over/) | Trả về hoặc đặt liên kết được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/zoomobject/hyperlink_manager/) | Trả về trình quản lý liên kết siêu văn bản.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/zoomobject/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/zoomobject/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/zoomobject/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/zoomobject/rotation/) | Trả về hoặc đặt số độ mà hình dạng được xoay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/zoomobject/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/zoomobject/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/zoomobject/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/zoomobject/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/zoomobject/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ hiển thị đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/zoomobject/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nên không nên coi nó là khóa duy nhất lâu dài.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/zoomobject/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, luôn không đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/zoomobject/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/zoomobject/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/zoomobject/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Phải không phải None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/zoomobject/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/zoomobject/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/zoomobject/is_grouped/) | Xác định xem hình dạng có được nhóm không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/zoomobject/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Ngược lại trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/zoomobject/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/zoomobject/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/zoomobject/graphical_object_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/vi/aspose.slides/zoomobject/image_type/) | Lấy hoặc đặt loại hình ảnh của một đối tượng zoom.<br/>            Đọc/ghi [`ZoomImageType`](/slides/python-net/vi/aspose.slides/zoomimagetype).<br/>            Giá trị mặc định: Preview |
| [`return_to_parent`](/slides/python-net/vi/aspose.slides/zoomobject/return_to_parent/) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: false |
| [`show_background`](/slides/python-net/vi/aspose.slides/zoomobject/show_background/) | Lấy hoặc đặt giá trị chỉ định Zoom có sử dụng nền của slide đích hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: true |
| [`zoom_image`](/slides/python-net/vi/aspose.slides/zoomobject/zoom_image/) | Lấy hoặc đặt hình ảnh cho đối tượng zoom.<br/>            Đọc/ghi [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/vi/aspose.slides/zoomobject/transition_duration/) | Lấy hoặc đặt thời lượng của chuyển đổi giữa Zoom và slide.<br/>            Đọc/ghi **float**.<br/>            Giá trị mặc định: 1.0f |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/zoomobject/get_image/#) | Trả về hình thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho ranh giới hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/zoomobject/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder cho một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/zoomobject/get_base_placeholder/#) | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide master mà hình dạng hiện tại kế thừa).<br/>            Trả về None nếu hình dạng hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/zoomobject/get_visual_bounds/#) | Lấy ranh giới trực quan của hình dạng được tính từ nội dung đã render. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)