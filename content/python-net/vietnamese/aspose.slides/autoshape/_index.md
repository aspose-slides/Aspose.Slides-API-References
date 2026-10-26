---
title: AutoShape class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/autoshape/
---
## Lớp AutoShape

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/vi/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

The AutoShape type exposes the following members:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/autoshape/is_text_holder/) | Xác định xem hình có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/autoshape/placeholder/) | Trả về placeholder cho một hình. Trả về None nếu hình không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/autoshape/custom_data/) | Trả về dữ liệu tùy chỉnh của hình.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/autoshape/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/autoshape/frame/) | Trả về hoặc đặt các thuộc tính khung hình.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/autoshape/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình.<br/>            Lưu ý: có thể trả về None cho một số loại hình không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/autoshape/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình.<br/>            Lưu ý: có thể trả về None cho một số loại hình không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/autoshape/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình.<br/>            Lưu ý: có thể trả về None cho một số loại hình không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/autoshape/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô đầy cho một hình.<br/>            Lưu ý: có thể trả về None cho một số loại hình không có thuộc tính tô đầy.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/autoshape/hyperlink_click/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/autoshape/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/autoshape/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/autoshape/hidden/) | Xác định xem hình có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/autoshape/z_order_position/) | Trả về vị trí của một hình trong thứ tự z.<br/>            Shapes[0] trả về hình ở phía sau cùng của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình ở phía trước cùng của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/autoshape/connection_site_count/) | Trả về số lượng điểm kết nối trên hình.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/autoshape/rotation/) | Trả về hoặc đặt số độ mà hình được quay quanh trục z.<br/>            Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/autoshape/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/autoshape/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/autoshape/width/) | Lấy hoặc đặt chiều rộng của hình, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/autoshape/height/) | Lấy hoặc đặt chiều cao của hình, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/autoshape/black_white_mode/) | Thuộc tính xác định cách một hình sẽ được hiển thị ở chế độ đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/autoshape/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không được coi là khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/autoshape/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, cố định trong suốt vòng đời của hình và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/autoshape/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên kết với một hình.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/autoshape/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/autoshape/name/) | Trả về hoặc đặt tên của một hình.<br/>            Không được để là None. Nếu cần, sử dụng chuỗi rỗng.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/autoshape/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/autoshape/shape_lock/) | Trả về các khóa của hình.<br/>            Chỉ đọc [`IAutoShapeLock`](/slides/python-net/vi/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/autoshape/is_grouped/) | Xác định xem hình có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/autoshape/parent_group/) | Trả về đối tượng GroupShape cha nếu hình được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/autoshape/slide/) | Trả về slide cha của một hình.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/autoshape/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/vi/aspose.slides/autoshape/shape_style/) | Trả về đối tượng style của hình.<br/>            Chỉ đọc [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides/autoshape/shape_type/) | Trả về hoặc đặt kiểu preset hình học.<br/>            Lưu ý: khi giá trị thay đổi, tất cả các giá trị điều chỉnh sẽ được đặt lại thành giá trị mặc định.<br/>            Đọc/ghi [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides/autoshape/adjustments/) | Trả về một tập hợp các giá trị điều chỉnh của hình.<br/>            Chỉ đọc [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/vi/aspose.slides/autoshape/auto_shape_lock/) | Trả về các khóa của autoshape.<br/>            Chỉ đọc [`IAutoShapeLock`](/slides/python-net/vi/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/vi/aspose.slides/autoshape/text_frame/) | Trả về đối tượng TextFrame cho AutoShape.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/vi/aspose.slides/autoshape/use_background_fill/) | Xác định xem autoshape này có nên được tô đầy bằng nền slide thay vì được chỉ định bởi style hoặc fill format hay không.<br/>            Đọc/ghi **bool**. |
| [`is_text_box`](/slides/python-net/vi/aspose.slides/autoshape/is_text_box/) | Xác định xem hình có phải là hộp văn bản hay không. |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/autoshape/get_image/#) | Trả về hình thu nhỏ của hình.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/autoshape/remove_placeholder/#) | Xác định rằng hình này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và đặt các thuộc tính placeholder thành một placeholder đã chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/autoshape/get_base_placeholder/#) | Trả về một hình placeholder cơ bản (hình từ bố cục và/hoặc slide master mà hình hiện tại kế thừa).<br/>            Trả về None nếu hình hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/autoshape/get_visual_bounds/#) | Lấy giới hạn hiển thị của hình được tính dựa trên nội dung đã render. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/autoshape/get_geometry_paths/#) | Trả về bản sao của đường dẫn của hình dạng hình học. Tọa độ tương đối với góc trên-trái của hình. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Cập nhật hình học của hình từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trên-trái của hình.<br/>             Thay đổi kiểu của hình ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Cập nhật hình học của hình từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trên-trái của hình.<br/>             Thay đổi kiểu của hình ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/autoshape/create_shape_elements/#) | Tạo và trả về mảng các phần tử của hình. |
| [`add_text_frame(self, text)`](/slides/python-net/vi/aspose.slides/autoshape/add_text_frame/#str) | Thêm một TextFrame mới vào một hình.<br/>            Nếu hình đã có TextFrame thì chỉ thay đổi văn bản của nó. |

### Xem thêm
* lớp [`AutoShape`](/slides/python-net/vi/aspose.slides/autoshape)
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)