---
title: AudioFrame class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/audioframe/
---
## AudioFrame lớp

Biểu diễn một đoạn âm thanh trên một slide.

**Inheritance:**[`AudioFrame`](/slides/python-net/vi/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu AudioFrame cung cấp các thành viên sau:

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/audioframe/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/audioframe/placeholder/) | Trả về trình giữ chỗ cho một hình dạng. Trả về None nếu hình dạng không có trình giữ chỗ.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/audioframe/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/audioframe/raw_frame/) | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/audioframe/frame/) | Trả về hoặc thiết lập các thuộc tính khung hình dạng.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/audioframe/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/audioframe/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/audioframe/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/audioframe/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None cho một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/audioframe/hyperlink_click/) | Trả về hoặc thiết lập liên kết siêu văn bản được định nghĩa cho nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/audioframe/hyperlink_mouse_over/) | Trả về hoặc thiết lập liên kết siêu văn bản được định nghĩa cho rê chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/audioframe/hyperlink_manager/) | Trả về trình quản lý liên kết siêu văn bản.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/audioframe/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/audioframe/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau nhất trong thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước nhất trong thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/audioframe/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/audioframe/rotation/) | Trả về hoặc thiết lập số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/audioframe/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/audioframe/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/audioframe/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/audioframe/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/audioframe/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/audioframe/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản thuyết trình, dự định dùng cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nó không được coi là khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/audioframe/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/audioframe/alternative_text/) | Trả về hoặc thiết lập văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/audioframe/alternative_text_title/) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một hình dạng.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/audioframe/name/) | Trả về hoặc thiết lập tên của một hình dạng.<br/>            Không được để None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/audioframe/is_decorative/) | Lấy hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/audioframe/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IPictureFrameLock`](/slides/python-net/vi/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/audioframe/is_grouped/) | Xác định xem hình dạng có được nhóm không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/audioframe/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/audioframe/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/audioframe/presentation/) | Trả về bản thuyết trình cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/vi/aspose.slides/audioframe/shape_style/) | Trả về đối tượng kiểu dáng của hình dạng.<br/>            Chỉ đọc [`IShapeStyle`](/slides/python-net/vi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/vi/aspose.slides/audioframe/shape_type/) | Trả về hoặc thiết lập loại AutoShape cho PictureFrame.<br/>            Tất cả các mục trong tập [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) đều được cho phép,<br/>            ngoại trừ các loại đường:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Đọc/ghi [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/vi/aspose.slides/audioframe/adjustments/) | Trả về một tập hợp các giá trị điều chỉnh của hình dạng.<br/>            Chỉ đọc [`IAdjustValueCollection`](/slides/python-net/vi/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/vi/aspose.slides/audioframe/picture_frame_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IPictureFrameLock`](/slides/python-net/vi/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/vi/aspose.slides/audioframe/picture_format/) | Trả về đối tượng PictureFillFormat cho một khung ảnh.<br/>            Chỉ đọc [`IPictureFillFormat`](/slides/python-net/vi/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/vi/aspose.slides/audioframe/relative_scale_height/) | Trả về hoặc thiết lập tỷ lệ chiều cao (so với kích thước ảnh gốc) của khung ảnh. Giá trị 1.0 ứng với 100%.<br/>            Đọc/ghi **float**. |
| [`relative_scale_width`](/slides/python-net/vi/aspose.slides/audioframe/relative_scale_width/) | Trả về hoặc thiết lập tỷ lệ chiều rộng (so với kích thước ảnh gốc) của khung ảnh. Giá trị 1.0 ứng với 100%.<br/>            Đọc/ghi **float**. |
| [`is_cameo`](/slides/python-net/vi/aspose.slides/audioframe/is_cameo/) | Xác định xem PictureFrame có phải là đối tượng Cameo hay không.<br/>            Chỉ đọc **bool**. |
| [`audio_cd_start_track`](/slides/python-net/vi/aspose.slides/audioframe/audio_cd_start_track/) | Trả về hoặc thiết lập chỉ mục track bắt đầu.<br/>            Đọc/ghi **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/vi/aspose.slides/audioframe/audio_cd_start_track_time/) | Trả về hoặc thiết lập thời gian track bắt đầu.<br/>            Đọc/ghi **int**. |
| [`audio_cd_end_track`](/slides/python-net/vi/aspose.slides/audioframe/audio_cd_end_track/) | Trả về hoặc thiết lập chỉ mục track cuối cùng<br/>            Đọc/ghi **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/vi/aspose.slides/audioframe/audio_cd_end_track_time/) | Trả về hoặc thiết lập thời gian track cuối cùng.<br/>            Đọc/ghi **int**. |
| [`volume`](/slides/python-net/vi/aspose.slides/audioframe/volume/) | Trả về hoặc thiết lập âm lượng âm thanh.<br/>            Đọc/ghi [`AudioVolumeMode`](/slides/python-net/vi/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/vi/aspose.slides/audioframe/play_mode/) | Trả về hoặc thiết lập chế độ phát âm thanh.<br/>            Đọc/ghi [`AudioPlayModePreset`](/slides/python-net/vi/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/vi/aspose.slides/audioframe/hide_at_showing/) | Xác định xem AudioFrame có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`play_loop_mode`](/slides/python-net/vi/aspose.slides/audioframe/play_loop_mode/) | Xác định xem âm thanh có được lặp lại hay không.<br/>            Đọc/ghi **bool**. |
| [`play_across_slides`](/slides/python-net/vi/aspose.slides/audioframe/play_across_slides/) | Xác định xem âm thanh có được phát xuyên suốt các slide hay không.<br/>            Đọc/ghi **bool**. |
| [`rewind_audio`](/slides/python-net/vi/aspose.slides/audioframe/rewind_audio/) | Xác định xem âm thanh có tự động tua lại về đầu sau khi phát hay không.<br/>            Đọc/ghi **bool**. |
| [`embedded`](/slides/python-net/vi/aspose.slides/audioframe/embedded/) | Xác định xem âm thanh có được nhúng vào bản thuyết trình hay không.<br/>            Chỉ đọc **bool**. |
| [`link_path_long`](/slides/python-net/vi/aspose.slides/audioframe/link_path_long/) | Trả về hoặc thiết lập tên của tệp âm thanh được liên kết với AudioFrame.<br/>            Đọc/ghi **str**. |
| [`embedded_audio`](/slides/python-net/vi/aspose.slides/audioframe/embedded_audio/) | Trả về hoặc thiết lập đối tượng âm thanh nhúng.<br/>            Đọc/ghi [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/vi/aspose.slides/audioframe/fade_in_duration/) | Xác định thời lượng (ms) cho hiệu ứng fade-in ban đầu của phương tiện.<br/>            Đọc/ghi **float**. |
| [`fade_out_duration`](/slides/python-net/vi/aspose.slides/audioframe/fade_out_duration/) | Xác định thời lượng (ms) cho hiệu ứng fade-out cuối cùng của phương tiện.<br/>            Đọc/ghi **float**. |
| [`volume_value`](/slides/python-net/vi/aspose.slides/audioframe/volume_value/) | Trả về hoặc thiết lập âm lượng âm thanh dưới dạng phần trăm.<br/>            Đọc/ghi **float**. |
| [`trim_from_start`](/slides/python-net/vi/aspose.slides/audioframe/trim_from_start/) | Xác định thời lượng (ms) cần loại bỏ khỏi phần đầu của phương tiện trong quá trình phát.<br/>            Đọc/ghi **float**. |
| [`trim_from_end`](/slides/python-net/vi/aspose.slides/audioframe/trim_from_end/) | Xác định thời lượng (ms) cần loại bỏ khỏi phần cuối của phương tiện trong quá trình phát.<br/>            Đọc/ghi **float**. |
| [`caption_tracks`](/slides/python-net/vi/aspose.slides/audioframe/caption_tracks/) | Lấy tập hợp các phụ đề đóng kèm với khung âm thanh.<br/>            Thuộc tính này chỉ đọc và trả về một [`ICaptionsCollection`](/slides/python-net/vi/aspose.slides/icaptionscollection) chứa tất cả các track phụ đề. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/audioframe/get_image/#) | Trả về hình thu nhỏ của hình dạng.<br/>            Kiểu bounds ShapeThumbnailBounds.Shape được sử dụng mặc định. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Lưu nội dung của Shape thành tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape thành tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/audioframe/remove_placeholder/#) | Xác định rằng hình dạng này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu chưa có và thiết lập các thuộc tính placeholder cho một placeholder đã chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/audioframe/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/audioframe/get_visual_bounds/#) | Lấy bounds trực quan của shape được tính từ nội dung đã render. |
| [`get_geometry_paths(self)`](/slides/python-net/vi/aspose.slides/audioframe/get_geometry_paths/#) | Trả về bản sao của đường dẫn của shape hình học. Các tọa độ tương đối với góc trái-trên của shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/vi/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Cập nhật hình học của shape từ đối tượng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối với góc trái-trên của shape.<br/>            Thay đổi kiểu của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/vi/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Cập nhật hình học của shape từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối với góc trái-trên của shape.<br/>            Thay đổi kiểu của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/vi/aspose.slides/audioframe/create_shape_elements/#) | Tạo và trả về mảng các phần tử của shape. |

### Xem thêm
* lớp [`AudioFrame`](/slides/python-net/vi/aspose.slides/audioframe)
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)