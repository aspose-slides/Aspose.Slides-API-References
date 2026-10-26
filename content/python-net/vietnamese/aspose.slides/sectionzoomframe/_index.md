---
title: SectionZoomFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame lớp

Đại diện cho một đối tượng Section Zoom trong một slide.

**Kế thừa:**[`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu SectionZoomFrame cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/sectionzoomframe/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/sectionzoomframe/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/sectionzoomframe/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/sectionzoomframe/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/sectionzoomframe/frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/sectionzoomframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/sectionzoomframe/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/sectionzoomframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/sectionzoomframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô đầy cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô đầy.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/sectionzoomframe/hyperlink_click/) | Trả về hoặc đặt liên kết siêu được định nghĩa cho lần nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | Trả về hoặc đặt liên kết siêu được định nghĩa khi di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/sectionzoomframe/hyperlink_manager/) | Trả về trình quản lý liên kết siêu.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/sectionzoomframe/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/sectionzoomframe/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau cùng của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước cùng của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/sectionzoomframe/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/sectionzoomframe/rotation/) | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/sectionzoomframe/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/sectionzoomframe/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/sectionzoomframe/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/sectionzoomframe/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/sectionzoomframe/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/sectionzoomframe/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, được dùng cho các add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nó không được xem như một khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/sectionzoomframe/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi cho slide, giữ nguyên trong suốt thời gian tồn tại của hình dạng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/sectionzoomframe/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/sectionzoomframe/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/sectionzoomframe/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Không được là None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/sectionzoomframe/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/sectionzoomframe/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/sectionzoomframe/is_grouped/) | Xác định xem hình dạng có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/sectionzoomframe/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/sectionzoomframe/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/sectionzoomframe/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/sectionzoomframe/graphical_object_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/vi/aspose.slides/sectionzoomframe/image_type/) | Lấy hoặc đặt loại ảnh của đối tượng zoom.<br/>            Đọc/ghi [`ZoomImageType`](/slides/python-net/vi/aspose.slides/zoomimagetype).<br/>            Giá trị mặc định: Preview |
| [`return_to_parent`](/slides/python-net/vi/aspose.slides/sectionzoomframe/return_to_parent/) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: false |
| [`show_background`](/slides/python-net/vi/aspose.slides/sectionzoomframe/show_background/) | Lấy hoặc đặt giá trị chỉ định Zoom có sử dụng nền của slide đích hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định: true |
| [`zoom_image`](/slides/python-net/vi/aspose.slides/sectionzoomframe/zoom_image/) | Lấy hoặc đặt ảnh cho đối tượng zoom.<br/>            Đọc/ghi [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/vi/aspose.slides/sectionzoomframe/transition_duration/) | Lấy hoặc đặt thời lượng chuyển tiếp giữa Zoom và slide.<br/>            Đọc/ghi **float**.<br/>            Giá trị mặc định: 1.0f |
| [`target_section`](/slides/python-net/vi/aspose.slides/sectionzoomframe/target_section/) | Lấy hoặc đặt đối tượng phần mà đối tượng Section Zoom liên kết tới.<br/>            Đọc/ghi [`ISection`](/slides/python-net/vi/aspose.slides/isection). |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/get_image/#) | Trả về ảnh thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn ảnh thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt thuộc tính placeholder cho một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/get_base_placeholder/#) | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide master mà hình dạng hiện tại kế thừa).<br/>            Trả về None nếu hình dạng hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/sectionzoomframe/get_visual_bounds/#) | Lấy giới hạn hình ảnh của hình dạng được tính từ nội dung đã render. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)