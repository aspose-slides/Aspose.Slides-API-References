---
title: OleObjectFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/oleobjectframe/
---
## OleObjectFrame lớp

Represents an OLE object on a slide.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/vi/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/oleobjectframe/is_text_holder/) | Xác định xem đối tượng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/oleobjectframe/placeholder/) | Trả về trình giữ chỗ cho một đối tượng. Trả về None nếu đối tượng không có trình giữ chỗ.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/oleobjectframe/custom_data/) | Trả về dữ liệu tùy chỉnh của đối tượng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/oleobjectframe/raw_frame/) | Lấy hoặc đặt các thuộc tính khung dạng thô của đối tượng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/oleobjectframe/frame/) | Lấy hoặc đặt các thuộc tính khung dạng của đối tượng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/oleobjectframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một đối tượng.<br/>            Lưu ý: có thể trả về None đối với một số loại đối tượng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/oleobjectframe/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một đối tượng.<br/>            Lưu ý: có thể trả về None đối với một số loại đối tượng không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/oleobjectframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một đối tượng.<br/>            Lưu ý: có thể trả về None đối với một số loại đối tượng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/oleobjectframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một đối tượng.<br/>            Lưu ý: có thể trả về None đối với một số loại đối tượng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/oleobjectframe/hyperlink_click/) | Lấy hoặc đặt siêu liên kết được định nghĩa cho click chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Lấy hoặc đặt siêu liên kết được định nghĩa cho rê chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/oleobjectframe/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/oleobjectframe/hidden/) | Xác định xem đối tượng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/oleobjectframe/z_order_position/) | Trả về vị trí của một đối tượng trong thứ tự z.<br/>            Shapes[0] trả về đối tượng ở phía sau trong thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về đối tượng ở phía trước trong thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/oleobjectframe/connection_site_count/) | Trả về số lượng điểm kết nối trên đối tượng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/oleobjectframe/rotation/) | Lấy hoặc đặt số độ mà đối tượng được chỉ định quay quanh trục z.<br/>            Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/oleobjectframe/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của đối tượng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/oleobjectframe/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của đối tượng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/oleobjectframe/width/) | Lấy hoặc đặt chiều rộng của đối tượng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/oleobjectframe/height/) | Lấy hoặc đặt chiều cao của đối tượng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/oleobjectframe/black_white_mode/) | Thuộc tính chỉ định cách một đối tượng sẽ hiển thị trong chế độ đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/oleobjectframe/unique_id/) | Trả về định danh nội bộ, có phạm vi trong bản trình chiếu, dự định cho các add-in hoặc mã khác sử dụng.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nó không được coi là khóa duy nhất ổn định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/oleobjectframe/office_interop_shape_id/) | Trả về định danh duy nhất có phạm vi trong slide, giữ nguyên trong suốt vòng đời của đối tượng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu đối tượng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/oleobjectframe/alternative_text/) | Lấy hoặc đặt văn bản thay thế liên kết với một đối tượng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/oleobjectframe/alternative_text_title/) | Lấy hoặc đặt tiêu đề của văn bản thay thế liên kết với một đối tượng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/oleobjectframe/name/) | Lấy hoặc đặt tên của một đối tượng.<br/>            Không được để None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/oleobjectframe/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/oleobjectframe/shape_lock/) | Trả về các khóa của đối tượng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/oleobjectframe/is_grouped/) | Xác định xem đối tượng có được nhóm không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/oleobjectframe/parent_group/) | Trả về đối tượng GroupShape cha nếu đối tượng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/oleobjectframe/slide/) | Trả về slide cha của một đối tượng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/oleobjectframe/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/oleobjectframe/graphical_object_lock/) | Trả về các khóa của đối tượng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/vi/aspose.slides/oleobjectframe/substitute_picture_format/) | Trả về đối tượng thuộc tính tô ảnh OleObject.<br/>            Chỉ đọc [`IPictureFillFormat`](/slides/python-net/vi/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/vi/aspose.slides/oleobjectframe/substitute_picture_title/) | Lấy hoặc đặt tiêu đề cho biểu tượng OleObject.<br/>            Đọc/ghi **str**. |
| [`object_name`](/slides/python-net/vi/aspose.slides/oleobjectframe/object_name/) | Lấy hoặc đặt tên của một đối tượng.<br/>            Đọc/ghi **str**. |
| [`object_prog_id`](/slides/python-net/vi/aspose.slides/oleobjectframe/object_prog_id/) | Trả về ProgID của một đối tượng.<br/>            Chỉ đọc **str**. |
| [`link_file_name`](/slides/python-net/vi/aspose.slides/oleobjectframe/link_file_name/) | Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp ngắn sẽ được sử dụng.<br/>            Chỉ đọc **str**. |
| [`link_path_long`](/slides/python-net/vi/aspose.slides/oleobjectframe/link_path_long/) | Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp dài sẽ được sử dụng.<br/>            Đọc/ghi **str**. |
| [`link_path_relative`](/slides/python-net/vi/aspose.slides/oleobjectframe/link_path_relative/) | Trả về đường dẫn tương đối tới tệp được liên kết nếu có, nếu không trả về chuỗi rỗng.<br/>             Chỉ đọc **str**. |
| [`embedded_file_label`](/slides/python-net/vi/aspose.slides/oleobjectframe/embedded_file_label/) | Trả về tên tệp của đối tượng OLE được nhúng |
| [`embedded_file_name`](/slides/python-net/vi/aspose.slides/oleobjectframe/embedded_file_name/) | Trả về đường dẫn của đối tượng OLE được nhúng |
| [`embedded_data`](/slides/python-net/vi/aspose.slides/oleobjectframe/embedded_data/) | Lấy hoặc đặt thông tin về dữ liệu OLE được nhúng.<br/>            Đọc/ghi [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/vi/aspose.slides/oleobjectframe/is_object_icon/) | Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng không.<br/>            Đọc/ghi **bool**. |
| [`is_object_link`](/slides/python-net/vi/aspose.slides/oleobjectframe/is_object_link/) | Xác định xem một đối tượng có được liên kết tới tệp bên ngoài không.<br/>            Chỉ đọc **bool**. |
| [`update_automatic`](/slides/python-net/vi/aspose.slides/oleobjectframe/update_automatic/) | Xác định xem đối tượng nhúng liên kết có được tự động cập nhật khi bản trình chiếu được mở hoặc in không.<br/>            Đọc/ghi **bool**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/oleobjectframe/get_image/#) | Trả về hình thu nhỏ của đối tượng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của đối tượng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Lưu nội dung của Đối tượng dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Đối tượng dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/oleobjectframe/remove_placeholder/#) | Xác định rằng đối tượng này không phải là trình giữ chỗ. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Thêm một trình giữ chỗ mới nếu không có và đặt các thuộc tính trình giữ chỗ thành một đối tượng được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/oleobjectframe/get_base_placeholder/#) | Trả về một hình dạng trình giữ chỗ cơ bản (hình dạng từ bố cục và/hoặc slide mẫu mà hình dạng hiện tại kế thừa).<br/>            Trả về None nếu hình dạng hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/oleobjectframe/get_visual_bounds/#) | Lấy giới hạn trực quan của đối tượng được tính từ nội dung đã hiển thị. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/vi/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Đặt thông tin về dữ liệu OLE được nhúng.<br/>            <br/>            Phương thức này thay đổi các thuộc tính của đối tượng để phản ánh dữ liệu mới và <br/>            đặt cờ IsObjectLink thành false, cho biết đối tượng OLE được nhúng. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`OleObjectFrame`](/slides/python-net/vi/aspose.slides/oleobjectframe)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)