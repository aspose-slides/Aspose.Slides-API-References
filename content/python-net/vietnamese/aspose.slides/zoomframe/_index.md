---
title: ZoomFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/zoomframe/
---
## ZoomFrame lớp

Biểu thị một đối tượng Slide Zoom trong một slide.

**Kế thừa:**[`ZoomFrame`](/slides/python-net/vi/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu ZoomFrame cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/zoomframe/is_text_holder/) | Xác định xem shape có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/zoomframe/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/zoomframe/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/zoomframe/raw_frame/) | Trả về hoặc đặt các thuộc tính khung shape thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/zoomframe/frame/) | Trả về hoặc đặt các thuộc tính khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/zoomframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/zoomframe/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/zoomframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/zoomframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/zoomframe/hyperlink_click/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho click chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/zoomframe/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/zoomframe/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/zoomframe/hidden/) | Xác định xem shape có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/zoomframe/z_order_position/) | Trả về vị trí của một shape trong thứ tự z.<br/>            Shapes[0] trả về shape ở phía sau nhất trong thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở phía trước nhất trong thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/zoomframe/connection_site_count/) | Trả về số lượng điểm kết nối trên shape.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/zoomframe/rotation/) | Trả về hoặc đặt số độ mà shape được quay quanh<br/>            trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm<br/>            biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/zoomframe/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/zoomframe/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/zoomframe/width/) | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/zoomframe/height/) | Lấy hoặc đặt chiều cao của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/zoomframe/black_white_mode/) | Thuộc tính chỉ định cách shape sẽ hiển thị ở chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/zoomframe/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dự định dùng cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nó không được xem như một khóa duy nhất bền vững.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/zoomframe/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, giữ nguyên trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/zoomframe/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan tới một shape.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/zoomframe/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan tới một shape.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/zoomframe/name/) | Trả về hoặc đặt tên của một shape.<br/>            Không được là None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/zoomframe/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/zoomframe/shape_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/zoomframe/is_grouped/) | Xác định xem shape có nằm trong nhóm không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/zoomframe/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/zoomframe/slide/) | Trả về slide cha của một shape.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/zoomframe/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/zoomframe/graphical_object_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/vi/aspose.slides/zoomframe/image_type/) | Lấy hoặc đặt loại hình ảnh của đối tượng zoom.<br/>            Đọc/ghi [`ZoomImageType`](/slides/python-net/vi/aspose.slides/zoomimagetype).<br/>            Giá trị mặc định: Preview |
| [`return_to_parent`](/slides/python-net/vi/aspose.slides/zoomframe/return_to_parent/) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: false |
| [`show_background`](/slides/python-net/vi/aspose.slides/zoomframe/show_background/) | Lấy hoặc đặt giá trị chỉ định Zoom có sử dụng nền của slide đích hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: true |
| [`zoom_image`](/slides/python-net/vi/aspose.slides/zoomframe/zoom_image/) | Lấy hoặc đặt hình ảnh cho đối tượng zoom.<br/>            Đọc/ghi [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/vi/aspose.slides/zoomframe/transition_duration/) | Lấy hoặc đặt thời lượng chuyển đổi giữa Zoom và slide.<br/>            Đọc/ghi **float**.<br/>            Giá trị mặc định: 1.0f |
| [`target_slide`](/slides/python-net/vi/aspose.slides/zoomframe/target_slide/) | Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới.<br/>            Đọc/ghi [`ISlide`](/slides/python-net/vi/aspose.slides/islide). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/zoomframe/get_image/#) | Trả về ảnh thu nhỏ của shape.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn ảnh thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/zoomframe/remove_placeholder/#) | Xác định rằng shape này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và đặt các thuộc tính placeholder cho một placeholder đã chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/zoomframe/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc master slide mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/zoomframe/get_visual_bounds/#) | Lấy giới hạn trực quan của shape được tính từ nội dung đã render. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`ZoomFrame`](/slides/python-net/vi/aspose.slides/zoomframe)
* lớp [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)