---
title: VideoFrame class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/videoframe/
---
## VideoFrame lớp

Biểu diễn một đoạn video trên một slide.

**Kế thừa:**[`VideoFrame`](/slides/python-net/vi/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu VideoFrame cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/videoframe/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/videoframe/placeholder/) | Trả về placeholder cho một hình dạng. Trả về None nếu hình dạng không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/videoframe/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/videoframe/raw_frame/) | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/videoframe/frame/) | Trả về hoặc thiết lập các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/videoframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/videoframe/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/videoframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/videoframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/videoframe/hyperlink_click/) | Trả về hoặc thiết lập hyperlink được định nghĩa cho nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/videoframe/hyperlink_mouse_over/) | Trả về hoặc thiết lập hyperlink được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/videoframe/hyperlink_manager/) | Trả về trình quản lý hyperlink.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/videoframe/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/videoframe/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/videoframe/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/videoframe/rotation/) | Trả về hoặc thiết lập số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/videoframe/x/) | Lấy hoặc thiết lập tọa độ x của góc trên-trái của hình dạng, tính bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/videoframe/y/) | Lấy hoặc thiết lập tọa độ y của góc trên-trái của hình dạng, tính bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/videoframe/width/) | Lấy hoặc thiết lập chiều rộng của hình dạng, tính bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/videoframe/height/) | Lấy hoặc thiết lập chiều cao của hình dạng, tính bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/videoframe/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị ở chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/videoframe/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, được dự định cho các add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nó không được xem như một khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/videoframe/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, không thay đổi trong thời gian tồn tại của hình dạng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/videoframe/alternative_text/) | Trả về hoặc thiết lập văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/videoframe/alternative_text_title/) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/videoframe/name/) | Trả về hoặc thiết lập tên của một hình dạng.<br/>            Phải không phải None. Nếu cần, dùng giá trị chuỗi rỗng.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/videoframe/is_decorative/) | Lấy hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/videoframe/shape_lock/) | Trả về khóa của hình dạng.<br/>            Chỉ đọc [`IPictureFrameLock`](/slides/python-net/vi/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/videoframe/is_grouped/) | Xác định xem hình dạng có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/videoframe/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/videoframe/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/videoframe/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/vi/aspose.slides/videoframe/shape_style/) | Trả về đối tượng style của hình dạng.<br/>            Chỉ đọc [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides/videoframe/shape_type/) | Trả về hoặc thiết lập loại AutoShape cho PictureFrame.<br/>            Tất cả các mục cho phép nằm trong tập [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype), <br/>            ngoại trừ mọi loại đường:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Đọc/ghi [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides/videoframe/adjustments/) | Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng.<br/>            Chỉ đọc [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/vi/aspose.slides/videoframe/picture_frame_lock/) | Trả về khóa của hình dạng.<br/>            Chỉ đọc [`IPictureFrameLock`](/slides/python-net/vi/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/vi/aspose.slides/videoframe/picture_format/) | Trả về đối tượng PictureFillFormat cho một picture frame.<br/>            Chỉ đọc [`IPictureFillFormat`](/slides/python-net/vi/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/vi/aspose.slides/videoframe/relative_scale_height/) | Trả về hoặc thiết lập tỷ lệ chiều cao (so với kích thước ảnh gốc) của picture frame. Giá trị 1.0 tương đương 100%.<br/>            Đọc/ghi **float**. |
| [`relative_scale_width`](/slides/python-net/vi/aspose.slides/videoframe/relative_scale_width/) | Trả về hoặc thiết lập tỷ lệ chiều rộng (so với kích thước ảnh gốc) của picture frame. Giá trị 1.0 tương đương 100%.<br/>            Đọc/ghi **float**. |
| [`is_cameo`](/slides/python-net/vi/aspose.slides/videoframe/is_cameo/) | Xác định xem PictureFrame có phải là đối tượng Cameo hay không.<br/>            Chỉ đọc **bool**. |
| [`rewind_video`](/slides/python-net/vi/aspose.slides/videoframe/rewind_video/) | Xác định xem video có tự động tua lại về đầu<br/>            ngay khi phim kết thúc phát không.<br/>            Đọc/ghi **bool**. |
| [`play_loop_mode`](/slides/python-net/vi/aspose.slides/videoframe/play_loop_mode/) | Xác định xem video có được lặp lại không.<br/>            Đọc/ghi **bool**. |
| [`hide_at_showing`](/slides/python-net/vi/aspose.slides/videoframe/hide_at_showing/) | Xác định xem VideoFrame có bị ẩn không.<br/>            Đọc/ghi **bool**. |
| [`volume`](/slides/python-net/vi/aspose.slides/videoframe/volume/) | Trả về hoặc thiết lập âm lượng âm thanh.<br/>            Đọc/ghi [`AudioVolumeMode`](/slides/python-net/vi/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/vi/aspose.slides/videoframe/volume_value/) | Trả về hoặc thiết lập âm lượng video chính xác dưới dạng phần trăm.<br/>             Giá trị được biểu diễn dưới dạng phần trăm từ 0 đến 100. Sử dụng thuộc tính này<br/>             để đọc hoặc thiết lập giá trị âm lượng chính xác hơn các mức đã định sẵn<br/>             thông qua thuộc tính [`VideoFrame.volume`](/slides/python-net/vi/aspose.slides/videoframe/volume).<br/>             Đọc/ghi **float**. |
| [`play_mode`](/slides/python-net/vi/aspose.slides/videoframe/play_mode/) | Trả về hoặc thiết lập chế độ phát video.<br/>            Đọc/ghi [`VideoPlayModePreset`](/slides/python-net/vi/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/vi/aspose.slides/videoframe/full_screen_mode/) | Xác định xem video có được hiển thị ở chế độ toàn màn hình không.<br/>            Đọc/ghi **bool**. |
| [`link_path_long`](/slides/python-net/vi/aspose.slides/videoframe/link_path_long/) | Trả về hoặc thiết lập tên của tệp video được liên kết với VideoFrame.<br/>            Đọc/ghi **str**. |
| [`embedded_video`](/slides/python-net/vi/aspose.slides/videoframe/embedded_video/) | Trả về hoặc thiết lập đối tượng video nhúng.<br/>            Đọc/ghi [`IVideo`](/slides/python-net/vi/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/vi/aspose.slides/videoframe/trim_from_start/) | Cắt đầu [ms] |
| [`trim_from_end`](/slides/python-net/vi/aspose.slides/videoframe/trim_from_end/) | Cắt kết thúc [ms] |
| [`caption_tracks`](/slides/python-net/vi/aspose.slides/videoframe/caption_tracks/) | Lấy bộ sưu tập các phụ đề đóng liên quan đến khung video.<br/>             Thuộc tính này chỉ đọc và trả về một [`ICaptionsCollection`](/slides/python-net/vi/aspose.slides/icaptionscollection) chứa tất cả các track phụ đề. |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/videoframe/get_image/#) | Trả về hình thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho phạm vi hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Lưu nội dung của Shape thành tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape thành tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/videoframe/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder cho một placeholder đã chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/videoframe/get_base_placeholder/#) | Trả về một hình placeholder cơ bản (hình từ bố cục và/hoặc slide master mà hình hiện tại kế thừa).<br/>            Trả về None nếu hình hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/videoframe/get_visual_bounds/#) | Lấy phạm vi hiển thị của hình dạng được tính từ nội dung đã render. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/videoframe/get_geometry_paths/#) | Trả về bản sao của đường dẫn của hình dạng geometry. Các tọa độ tính tương đối so với góc trên-trái của hình dạng. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Cập nhật geometry của hình dạng từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tính tương đối so với góc trên-trái<br/>             của hình dạng.<br/>             Thay đổi loại hình dạng ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Cập nhật geometry của hình dạng từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tính tương đối so với góc trên-trái<br/>             của hình dạng.<br/>             Thay đổi loại hình dạng ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/videoframe/create_shape_elements/#) | Tạo và trả về mảng các phần tử của hình dạng. |

### Xem thêm
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`VideoFrame`](/slides/python-net/vi/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)