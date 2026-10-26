---
title: SmartArtShape class
second_title: Tham chiếu API .NET cho Aspose.Slides cho Python
description: 
type: docs
url: /vi/aspose.slides.smartart/smartartshape/
---
## Lớp SmartArtShape

Biểu diễn hình dạng SmartArt

**Kế thừa:**[`SmartArtShape`](/slides/python-net/vi/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu SmartArtShape cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/hyperlink_click/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho thao tác di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/hidden/) | Xác định xem hình dạng có ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/connection_site_count/) | Trả về số vị trí kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/rotation/) | Trả về hoặc đặt số độ mà hình dạng được xoay quanh trục z.<br/>            Giá trị dương cho biết xoay theo chiều kim đồng hồ; giá trị âm cho biết xoay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ được hiển thị ở chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/unique_id/) | Trả về một định danh nội bộ, phạm vi bản trình chiếu, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên coi nó là khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Trả về định danh duy nhất phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Không được để là None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IBaseShapeLock`](/slides/python-net/vi/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/is_grouped/) | Xác định xem hình dạng có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/shape_style/) | Trả về đối tượng style của hình dạng.<br/>            Chỉ đọc [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/shape_type/) | Trả về hoặc đặt loại thiết lập geometry preset.<br/>            Lưu ý: khi giá trị thay đổi, tất cả các giá trị điều chỉnh sẽ được đặt lại về mặc định.<br/>            Đọc/ghi [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/adjustments/) | Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng.<br/>            Chỉ đọc [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/text_frame/) | Trả về văn bản của hình dạng SmartArt.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/get_image/#) | Trả về ảnh thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Thêm placeholder mới nếu không có và đặt thuộc tính placeholder thành một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Lấy giới hạn hiển thị trực quan của shape được tính từ nội dung đã render. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Trả về bản sao của đường dẫn của shape geometry. Tọa độ tương đối với góc trên-trái của shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Cập nhật geometry của shape từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trên-trái của shape.<br/>             Thay đổi loại shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Cập nhật geometry của shape từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trên-trái của shape.<br/>             Thay đổi loại shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Tạo và trả về mảng các phần tử của shape. |

### Xem Thêm
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`SmartArtShape`](/slides/python-net/vi/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)