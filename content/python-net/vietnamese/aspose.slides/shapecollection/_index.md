---
title: ShapeCollection class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/shapecollection/
---
## ShapeCollection lớp

Đại diện cho một bộ sưu tập các hình dạng.

Kiểu ShapeCollection cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`parent_group`](/slides/python-net/vi/aspose.slides/shapecollection/parent_group/) | Lấy đối tượng hình dạng nhóm cha cho bộ sưu tập hình dạng.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |

Lấy phần tử tại chỉ mục đã chỉ định.
            Chỉ đọc [`IShape`](/slides/python-net/vi/aspose.slides/ishape).

## Chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides/shapecollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm<br/>            nó vào cuối bộ sưu tập hình dạng. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/vi/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm<br/>            nó vào cuối bộ sưu tập hình dạng. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu,<br/>            và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu,<br/>            và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/vi/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/vi/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Tạo một khung Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Tạo một khung Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập hình dạng<br/>            tại chỉ mục đã chỉ định. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/vi/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Tạo một khung Zoom phần mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/vi/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Tạo một khung Zoom phần mới với hình ảnh đã định trước và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Tạo một khung Zoom phần mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Tạo một khung Zoom phần mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập<br/>            hình dạng tại chỉ mục đã chỉ định. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/vi/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/vi/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/vi/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/vi/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/vi/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Tạo một khung âm thanh mới với tệp WAV được nhúng và thêm nó vào cuối<br/>            bộ sưu tập hình dạng. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/vi/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập hình dạng bằng một<br/>            đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào bộ sưu tập<br/>            hình dạng tại chỉ mục đã chỉ định. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định<br/>            bằng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/vi/aspose.slides/shapecollection/to_array/#) | Tạo và trả về một mảng chứa tất cả các hình dạng. |
| [`to_array(self, start_index, count)`](/slides/python-net/vi/aspose.slides/shapecollection/to_array/#int-int) | Tạo và trả về một mảng chứa tất cả các hình dạng trong phạm vi đã chỉ định. |
| [`reorder(self, index, shape)`](/slides/python-net/vi/aspose.slides/shapecollection/reorder/#int-ishape) | Di chuyển hình dạng đã chỉ định đến vị trí mới trong bộ sưu tập hình dạng. |
| [`reorder(self, index, shapes)`](/slides/python-net/vi/aspose.slides/shapecollection/reorder/#int-listishape) | Di chuyển các hình dạng đã chỉ định trong bộ sưu tập hình dạng, đặt chúng bắt đầu từ chỉ mục đã cho. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Tạo một hình dạng tự động mới với định dạng mặc định và thêm nó vào cuối<br/>            bộ sưu tập hình dạng. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/vi/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Tạo một hình dạng tự động mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn<br/>            khởi tạo nó với định dạng mẫu mặc định. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Tạo một hình dạng tự động mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định,<br/>            áp dụng định dạng mẫu mặc định. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Tạo một hình dạng tự động mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định,<br/>            tùy chọn khởi tạo nó với kiểu mẫu mặc định. |
| [`add_group_shape(self)`](/slides/python-net/vi/aspose.slides/shapecollection/add_group_shape/#) | Tạo một nhóm hình dạng trống mới và thêm nó vào cuối bộ sưu tập hình dạng.<br/>            Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ hình dạng nào được thêm vào. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Tạo một nhóm hình dạng mới, chuyển đổi hình ảnh SVG đã chỉ định thành các hình dạng riêng lẻ,<br/>            và thêm nhóm kết quả vào cuối bộ sưu tập hình dạng. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Tạo một hình nối mới với kiểu mẫu mặc định và thêm nó vào cuối<br/>            bộ sưu tập hình dạng. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/vi/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Tạo một hình nối mới và thêm nó vào cuối bộ sưu tập hình dạng,<br/>            tùy chọn áp dụng kiểu mẫu mặc định. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Tạo một hình nối mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định,<br/>            áp dụng kiểu mẫu mặc định. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Tạo một hình nối mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định,<br/>            tùy chọn áp dụng kiểu mẫu mặc định. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/vi/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng.<br/>            Hình dạng mới giữ nguyên chiều rộng và chiều cao của `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/vi/aspose.slides/shapecollection/add_clone/#ishape) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng.<br/>            Hình dạng sao chép giữ nguyên vị trí và kích thước gốc. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.<br/>            Hình dạng mới giữ nguyên chiều rộng và chiều cao của `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_clone/#int-ishape) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.<br/>            Hình dạng sao chép giữ nguyên vị trí và kích thước gốc. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/vi/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Tạo một sơ đồ SmartArt và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Tạo một khung Summary Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Tạo một khung Summary Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Tạo một khung video mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Tạo một khung âm thanh mới liên kết tới một rãnh CD và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Tạo một khung âm thanh mới liên kết tới một rãnh CD và chèn nó vào bộ sưu tập hình dạng<br/>            tại chỉ mục đã chỉ định. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/vi/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Tạo một khung âm thanh mới liên kết tới một tệp âm thanh bên ngoài và thêm nó vào cuối<br/>            bộ sưu tập hình dạng. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Tạo một khung âm thanh mới liên kết tới một tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập<br/>            hình dạng tại chỉ mục đã chỉ định. |
| [`index_of(self, shape)`](/slides/python-net/vi/aspose.slides/shapecollection/index_of/#ishape) | Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng đã chỉ định trong bộ sưu tập. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/vi/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Tạo một hình dạng tự động hình chữ nhật mới để chứa nội dung toán học và thêm nó vào<br/>            cuối bộ sưu tập hình dạng. |
| [`insert_group_shape(self, index)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_group_shape/#int) | Tạo một nhóm hình dạng trống mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.<br/>            Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ hình dạng nào được thêm vào. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/vi/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Tạo một khung ảnh mới chứa hình ảnh đã chỉ định và thêm nó vào cuối<br/>            bộ sưu tập hình dạng. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Tạo một khung ảnh mới chứa hình ảnh đã chỉ định và chèn nó vào bộ sưu tập<br/>            hình dạng tại chỉ mục đã chỉ định. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/vi/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Tạo một bảng mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/vi/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Tạo một bảng mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides/shapecollection/remove_at/#int) | Xóa hình dạng tại chỉ mục đã chỉ định khỏi bộ sưu tập hình dạng. |
| [`remove(self, shape)`](/slides/python-net/vi/aspose.slides/shapecollection/remove/#ishape) | Xóa lần xuất hiện đầu tiên của hình dạng đã chỉ định khỏi bộ sưu tập hình dạng. |
| [`clear(self)`](/slides/python-net/vi/aspose.slides/shapecollection/clear/#) | Xóa tất cả các hình dạng khỏi bộ sưu tập hình dạng. |

### Xem thêm
* lớp [`IShape`](/slides/python-net/vi/aspose.slides/ishape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)