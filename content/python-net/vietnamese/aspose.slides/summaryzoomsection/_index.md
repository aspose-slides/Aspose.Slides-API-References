---
title: SummaryZoomSection class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/summaryzoomsection/
---
## Lớp SummaryZoomSection

Đại diện cho một đối tượng Summary Zoom Section trong một khung Summary Zoom.

**Kế thừa:**[`SummaryZoomSection`](/slides/python-net/vi/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu SummaryZoomSection cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/summaryzoomsection/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/summaryzoomsection/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/summaryzoomsection/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/summaryzoomsection/raw_frame/) | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/summaryzoomsection/frame/) | Trả về hoặc thiết lập các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/summaryzoomsection/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/summaryzoomsection/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/summaryzoomsection/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/summaryzoomsection/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/summaryzoomsection/hyperlink_click/) | Trả về hoặc thiết lập hyperlink được định nghĩa cho click chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Trả về hoặc thiết lập hyperlink được định nghĩa cho rê chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/summaryzoomsection/hyperlink_manager/) | Trả về trình quản lý hyperlink.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/summaryzoomsection/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/summaryzoomsection/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/summaryzoomsection/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/summaryzoomsection/rotation/) | Trả về hoặc thiết lập số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/summaryzoomsection/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/summaryzoomsection/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/summaryzoomsection/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/summaryzoomsection/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/summaryzoomsection/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ được hiển thị trong chế độ đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/summaryzoomsection/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình bày, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không được coi là khóa duy nhất lâu dài.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/summaryzoomsection/alternative_text/) | Trả về hoặc thiết lập văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/summaryzoomsection/alternative_text_title/) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/summaryzoomsection/name/) | Trả về hoặc thiết lập tên của một hình dạng.<br/>            Không được để là None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/summaryzoomsection/is_decorative/) | Lấy hoặc thiết lập tùy chọn 'Mark as decorative'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/summaryzoomsection/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/summaryzoomsection/is_grouped/) | Xác định xem hình dạng có được nhóm không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/summaryzoomsection/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/summaryzoomsection/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/summaryzoomsection/presentation/) | Trả về bản trình bày cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/summaryzoomsection/graphical_object_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/vi/aspose.slides/summaryzoomsection/image_type/) | Lấy hoặc thiết lập loại ảnh của đối tượng zoom.<br/>            Đọc/ghi [`ZoomImageType`](/slides/python-net/vi/aspose.slides/zoomimagetype).<br/>            Giá trị mặc định: Preview |
| [`return_to_parent`](/slides/python-net/vi/aspose.slides/summaryzoomsection/return_to_parent/) | Lấy hoặc thiết lập hành vi điều hướng trong trình chiếu.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: false |
| [`show_background`](/slides/python-net/vi/aspose.slides/summaryzoomsection/show_background/) | Lấy hoặc thiết lập giá trị cho biết Zoom có sử dụng nền của slide đích hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: true |
| [`zoom_image`](/slides/python-net/vi/aspose.slides/summaryzoomsection/zoom_image/) | Lấy hoặc thiết lập ảnh cho đối tượng zoom.<br/>            Đọc/ghi [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/vi/aspose.slides/summaryzoomsection/transition_duration/) | Lấy hoặc thiết lập thời lượng chuyển đổi giữa Zoom và slide.<br/>            Đọc/ghi **float**.<br/>            Giá trị mặc định: 1.0f |
| [`target_section`](/slides/python-net/vi/aspose.slides/summaryzoomsection/target_section/) | Lấy hoặc thiết lập đối tượng section mà đối tượng Section Zoom liên kết tới.<br/>            Đọc/ghi [`ISection`](/slides/python-net/vi/aspose.slides/isection). |
| [`title`](/slides/python-net/vi/aspose.slides/summaryzoomsection/title/) | Trả về tiêu đề văn bản của đối tượng Summary Zoom Section. |
| [`description`](/slides/python-net/vi/aspose.slides/summaryzoomsection/description/) | Trả về mô tả văn bản của đối tượng Summary Zoom Section. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/get_image/#) | Trả về hình thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và thiết lập các thuộc tính placeholder thành một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Trả về một hình placeholder cơ bản (hình từ bố cục và/hoặc slide master mà hình hiện tại kế thừa).<br/>            Trả về None nếu hình hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`SummaryZoomSection`](/slides/python-net/vi/aspose.slides/summaryzoomsection)
* lớp [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)