---
title: Connector class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/connector/
---
## Lớp Connector

Miêu tả một connector.

**Kế thừa:**[`Connector`](/slides/python-net/vi/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu Connector cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/connector/is_text_holder/) | Xác định xem shape có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/connector/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/connector/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/connector/raw_frame/) | Trả về hoặc thiết lập các thuộc tính thô của khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/connector/frame/) | Trả về hoặc thiết lập các thuộc tính khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/connector/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/connector/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/connector/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/connector/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/connector/hyperlink_click/) | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho việc nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/connector/hyperlink_mouse_over/) | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho việc di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/connector/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/connector/hidden/) | Xác định xem shape có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/connector/z_order_position/) | Trả về vị trí của shape trong thứ tự z.<br/>            Shapes[0] trả về shape ở phía sau cùng của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/connector/connection_site_count/) | Trả về số lượng điểm kết nối trên shape.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/connector/rotation/) | Trả về hoặc thiết lập số độ mà shape được quay quanh trục z.<br/>            Giá trị dương thể hiện quay theo chiều kim đồng hồ; giá trị âm thể hiện quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/connector/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/connector/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/connector/width/) | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/connector/height/) | Lấy hoặc đặt chiều cao của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/connector/black_white_mode/) | Thuộc tính chỉ định cách shape sẽ hiển thị trong chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/connector/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không được coi là khóa duy nhất bền vững.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/connector/office_interop_shape_id/) | Trả về một định danh duy nhất trong slide, giữ nguyên trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/connector/alternative_text/) | Trả về hoặc thiết lập văn bản thay thế liên quan đến shape.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/connector/alternative_text_title/) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến shape.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/connector/name/) | Trả về hoặc thiết lập tên của shape.<br/>            Không được để None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/connector/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/connector/shape_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IConnectorLock`](/slides/python-net/vi/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/connector/is_grouped/) | Xác định xem shape có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/connector/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/connector/slide/) | Trả về slide cha của shape.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/connector/presentation/) | Trả về bản trình chiếu cha của slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/vi/aspose.slides/connector/shape_style/) | Trả về đối tượng style của shape.<br/>            Chỉ đọc [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides/connector/shape_type/) | Trả về hoặc thiết lập kiểu AutoShape.<br/>            Đọc/ghi [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides/connector/adjustments/) | Trả về một bộ sưu tập các giá trị điều chỉnh của shape.<br/>            Chỉ đọc [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/vi/aspose.slides/connector/connector_lock/) | Trả về các khóa của connector.<br/>            Chỉ đọc [`IConnectorLock`](/slides/python-net/vi/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/vi/aspose.slides/connector/start_shape_connected_to/) | Trả về hoặc thiết lập shape để gắn đầu nối ở đầu.<br/>            Đọc/ghi [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/vi/aspose.slides/connector/end_shape_connected_to/) | Trả về hoặc thiết lập shape để gắn đầu nối ở cuối.<br/>            Đọc/ghi [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/vi/aspose.slides/connector/start_shape_connection_site_index/) | Trả về hoặc thiết lập chỉ mục của điểm kết nối cho shape bắt đầu.<br/>            Đọc/ghi **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/vi/aspose.slides/connector/end_shape_connection_site_index/) | Trả về hoặc thiết lập chỉ mục của điểm kết nối cho shape kết thúc.<br/>            Đọc/ghi **int**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/connector/get_image/#) | Trả về hình thu nhỏ của shape.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/connector/write_as_svg/#iorawiobase) | Lưu nội dung Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/connector/remove_placeholder/#) | Xác định rằng shape này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/connector/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và thiết lập các thuộc tính placeholder cho một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/connector/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/connector/get_visual_bounds/#) | Lấy giới hạn trực quan của shape được tính từ nội dung đã được render. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/connector/get_geometry_paths/#) | Trả về bản sao của đường dẫn của shape hình học. Tọa độ tương đối với góc trái-trên của shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/connector/set_geometry_path/#igeometrypath) | Cập nhật hình học của shape từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trái-trên của shape.<br/>            Thay đổi loại của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Cập nhật hình học của shape từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trái-trên của shape.<br/>            Thay đổi loại của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/connector/create_shape_elements/#) | Tạo và trả về mảng các phần tử của shape. |
| [`reroute(self)`](/slides/python-net/vi/aspose.slides/connector/reroute/#) | Định hướng lại connector sao cho nó lấy đường ngắn nhất có thể giữa các shape mà nó kết nối. |


### Xem thêm
* lớp [`Connector`](/slides/python-net/vi/aspose.slides/connector)
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)