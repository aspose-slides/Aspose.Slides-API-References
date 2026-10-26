---
title: PictureFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/pictureframe/
---
## Lớp PictureFrame

Biểu diễn một khung có hình ảnh bên trong.

**Inheritance:**[`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu PictureFrame cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/pictureframe/is_text_holder/) | Xác định xem shape có phải là TextHolder_PPT hay không.<br/>            **Chỉ đọc** **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/pictureframe/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            **Chỉ đọc** [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/pictureframe/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            **Chỉ đọc** [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/pictureframe/raw_frame/) | Trả về hoặc đặt các thuộc tính khung shape thô.<br/>            **Đọc/ghi** [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/pictureframe/frame/) | Trả về hoặc đặt các thuộc tính khung shape.<br/>            **Đọc/ghi** [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/pictureframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính đường.<br/>            **Chỉ đọc** [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/pictureframe/three_d_format/) | Trả về đối tượng ThreeDFormat có các thuộc tính hiệu ứng 3d cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính 3d.<br/>            **Chỉ đọc** [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/pictureframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính hiệu ứng.<br/>            **Chỉ đọc** [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/pictureframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng nền cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính nền.<br/>            **Chỉ đọc** [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/pictureframe/hyperlink_click/) | Trả về hoặc đặt hyperlink được định nghĩa cho click chuột.<br/>            **Đọc/ghi** [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/pictureframe/hyperlink_mouse_over/) | Trả về hoặc đặt hyperlink được định nghĩa cho rê chuột.<br/>            **Đọc/ghi** [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/pictureframe/hyperlink_manager/) | Trả về trình quản lý hyperlink.<br/>            **Chỉ đọc** [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/pictureframe/hidden/) | Xác định xem shape có bị ẩn hay không.<br/>            **Đọc/ghi** **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/pictureframe/z_order_position/) | Trả về vị trí của shape trong thứ tự z.<br/>            Shapes[0] trả về shape ở cuối chuỗi z,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở đầu chuỗi z.<br/>            **Chỉ đọc** **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/pictureframe/connection_site_count/) | Trả về số lượng điểm kết nối trên shape.<br/>            **Chỉ đọc** **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/pictureframe/rotation/) | Trả về hoặc đặt số độ mà shape được quay quanh trục z.<br/>            Giá trị dương chỉ chiều quay theo kim đồng hồ; giá trị âm chỉ chiều quay ngược kim đồng hồ.<br/>            **Đọc/ghi** **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/pictureframe/x/) | Lấy hoặc đặt tọa độ x của góc trái trên của shape, đo bằng point.<br/>            **Đọc/ghi** **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/pictureframe/y/) | Lấy hoặc đặt tọa độ y của góc trái trên của shape, đo bằng point.<br/>            **Đọc/ghi** **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/pictureframe/width/) | Lấy hoặc đặt chiều rộng của shape, đo bằng point.<br/>            **Đọc/ghi** **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/pictureframe/height/) | Lấy hoặc đặt chiều cao của shape, đo bằng point.<br/>            **Đọc/ghi** **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/pictureframe/black_white_mode/) | Thuộc tính xác định cách shape sẽ được hiển thị trong chế độ đen trắng..<br/>            **Đọc/ghi** [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/pictureframe/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dùng cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không nên coi là khóa duy nhất kéo dài.<br/>            **Chỉ đọc** **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/pictureframe/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, không thay đổi trong suốt vòng đời của shape và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            **Chỉ đọc** **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/pictureframe/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan đến shape.<br/>            **Đọc/ghi** **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/pictureframe/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến shape.<br/>            **Đọc/ghi** **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/pictureframe/name/) | Trả về hoặc đặt tên của shape.<br/>            Không được None. Nếu cần, sử dụng chuỗi rỗng.<br/>            **Đọc/ghi** **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/pictureframe/is_decorative/) | Lấy hoặc đặt tùy chọn 'Mark as decorative'<br/>            **Đọc/ghi** **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/pictureframe/shape_lock/) | Trả về các khóa của shape.<br/>            **Chỉ đọc** [`IPictureFrameLock`](/slides/python-net/vi/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/pictureframe/is_grouped/) | Xác định xem shape có được nhóm hay không.<br/>            **Chỉ đọc** **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/pictureframe/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về None.<br/>            **Chỉ đọc** [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/pictureframe/slide/) | Trả về slide cha của shape.<br/>            **Chỉ đọc** [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/pictureframe/presentation/) | Trả về bản trình chiếu cha của slide.<br/>            **Chỉ đọc** [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/vi/aspose.slides/pictureframe/shape_style/) | Trả về đối tượng style của shape.<br/>            **Chỉ đọc** [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides/pictureframe/shape_type/) | Trả về hoặc đặt loại AutoShape cho PictureFrame.<br/>            Tất cả các mục cho phép nằm trong tập [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype), <br/>            ngoại trừ các loại đường:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            **Đọc/ghi** [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides/pictureframe/adjustments/) | Trả về một tập hợp các giá trị điều chỉnh của shape.<br/>            **Chỉ đọc** [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/vi/aspose.slides/pictureframe/picture_frame_lock/) | Trả về các khóa của shape.<br/>            **Chỉ đọc** [`IPictureFrameLock`](/slides/python-net/vi/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/vi/aspose.slides/pictureframe/picture_format/) | Trả về đối tượng PictureFillFormat cho picture frame.<br/>            **Chỉ đọc** [`IPictureFillFormat`](/slides/python-net/vi/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/vi/aspose.slides/pictureframe/relative_scale_height/) | Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước ảnh gốc) của picture frame. Giá trị 1.0 tương đương 100%.<br/>            **Đọc/ghi** **float**. |
| [`relative_scale_width`](/slides/python-net/vi/aspose.slides/pictureframe/relative_scale_width/) | Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước ảnh gốc) của picture frame. Giá trị 1.0 tương đương 100%.<br/>            **Đọc/ghi** **float**. |
| [`is_cameo`](/slides/python-net/vi/aspose.slides/pictureframe/is_cameo/) | Xác định xem PictureFrame có phải là đối tượng Cameo hay không.<br/>            **Chỉ đọc** **bool**. |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/pictureframe/get_image/#) | Trả về hình thu nhỏ của shape.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/pictureframe/remove_placeholder/#) | Xác định rằng shape này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và đặt các thuộc tính placeholder thành một placeholder đã chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/pictureframe/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/pictureframe/get_visual_bounds/#) | Lấy giới hạn hình ảnh của shape tính toán từ nội dung đã render. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/pictureframe/get_geometry_paths/#) | Trả về bản sao của đường dẫn của shape hình học. Các tọa độ tương đối với góc trái trên của shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Cập nhật hình học của shape từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối với góc trái<br/>             trên của shape.<br/>             Thay đổi loại của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Cập nhật hình học của shape từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối với góc trái<br/>             trên của shape.<br/>             Thay đổi loại của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/pictureframe/create_shape_elements/#) | Tạo và trả về mảng các phần tử của shape. |

### Xem thêm
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)