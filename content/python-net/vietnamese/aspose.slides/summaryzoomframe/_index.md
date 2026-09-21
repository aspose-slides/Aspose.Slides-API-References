---
title: SummaryZoomFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame lớp

Đại diện cho một đối tượng Summary Zoom trong một slide.

**Inheritance:**[`SummaryZoomFrame`](/slides/python-net/vi/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu SummaryZoomFrame tiết lộ các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/summaryzoomframe/is_text_holder/) | Xác định liệu hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ-đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/summaryzoomframe/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ-đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/summaryzoomframe/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ-đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/summaryzoomframe/raw_frame/) | Trả về hoặc đặt các thuộc tính của khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/summaryzoomframe/frame/) | Trả về hoặc đặt các thuộc tính của khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/summaryzoomframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ-đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/summaryzoomframe/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3D.<br/>            Chỉ-đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/summaryzoomframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ-đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/summaryzoomframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ-đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/summaryzoomframe/hyperlink_click/) | Trả về hoặc đặt hyperlink được định nghĩa cho nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | Trả về hoặc đặt hyperlink được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/summaryzoomframe/hyperlink_manager/) | Trả về trình quản lý hyperlink.<br/>            Chỉ-đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/summaryzoomframe/hidden/) | Xác định liệu hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/summaryzoomframe/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau cùng của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước cùng của thứ tự z.<br/>            Chỉ-đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/summaryzoomframe/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ-đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/summaryzoomframe/rotation/) | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm<br/>            biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/summaryzoomframe/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/summaryzoomframe/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/summaryzoomframe/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/summaryzoomframe/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/summaryzoomframe/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị ở chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/summaryzoomframe/unique_id/) | Trả về một định danh nội bộ, phạm vi bản trình bày, được dự định để sử dụng bởi các add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nó không được coi là<br/>            một khóa duy nhất bền vững.<br/>            Chỉ-đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/summaryzoomframe/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ-đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/summaryzoomframe/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/summaryzoomframe/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/summaryzoomframe/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Phải không phải None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/summaryzoomframe/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/summaryzoomframe/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ-đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/summaryzoomframe/is_grouped/) | Xác định liệu hình dạng có được nhóm không.<br/>            Chỉ-đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/summaryzoomframe/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ-đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/summaryzoomframe/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ-đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/summaryzoomframe/presentation/) | Trả về bản trình bày cha của một slide.<br/>            Chỉ-đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/summaryzoomframe/graphical_object_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ-đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/vi/aspose.slides/summaryzoomframe/layout/) | Lấy bố cục của các phần Summary Zoom trong khung.<br/>            Giá trị mặc định là GridLayout. |
| [`summary_zoom_collection`](/slides/python-net/vi/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Lấy [`ISummaryZoomSectionCollection`](/slides/python-net/vi/aspose.slides/isummaryzoomsectioncollection) cho đối tượng Summary Zoom Frame. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/get_image/#) | Trả về ảnh thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn ảnh thu nhỏ của hình dạng. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/remove_placeholder/#) | Xác định rằng hình dạng này không phải là một placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder cho placeholder đã chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide mẫu mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/summaryzoomframe/get_visual_bounds/#) | Lấy giới hạn trực quan của shape được tính từ nội dung đã render. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`SummaryZoomFrame`](/slides/python-net/vi/aspose.slides/summaryzoomframe)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)