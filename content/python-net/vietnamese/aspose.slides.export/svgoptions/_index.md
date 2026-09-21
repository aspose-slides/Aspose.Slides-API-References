---
title: SVGOptions class
second_title: Aspose.Slides cho Python thông qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides.export/svgoptions/
---
## Lớp SVGOptions

Biểu diễn một tùy chọn SVG.

**Kế thừa:**[`SVGOptions`](/slides/python-net/vi/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu SVGOptions cung cấp các thành viên sau:

## Hàm tạo

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/svgoptions/__init__/#) | Khởi tạo một thể hiện mới của lớp SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/vi/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng bộ điều khiển nhúng liên kết. |

## Thuộc tính

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/svgoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/svgoptions/progress_callback/) | Biểu diễn một đối tượng callback để lưu cập nhật tiến độ ở dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/svgoptions/default_regular_font/) | Trả về hoặc đặt phông chữ được sử dụng khi không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/svgoptions/gradient_style/) | Trả về hoặc đặt kiểu hiển thị của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/svgoptions/skip_java_script_links/) | Xác định có bỏ qua các siêu liên kết có lệnh JavaScript khi lưu bản trình chiếu hay không.<br/>            Đọc/ghi **bool**. Giá trị mặc định là **false**. |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/svgoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/vi/aspose.slides.export/svgoptions/use_frame_size/) | Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định là false. |
| [`use_frame_rotation`](/slides/python-net/vi/aspose.slides.export/svgoptions/use_frame_rotation/) | Xác định có thực hiện việc quay hình dạng theo chỉ định khi render hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định là true. |
| [`vectorize_text`](/slides/python-net/vi/aspose.slides.export/svgoptions/vectorize_text/) | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không.<br/>            Đọc/ghi **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/vi/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Trả về hoặc đặt giới hạn độ phân giải thấp nhất cho raster hóa metafile.<br/>            Đọc/ghi **int**. |
| [`disable_3d_text`](/slides/python-net/vi/aspose.slides.export/svgoptions/disable_3d_text/) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không.<br/>            Đọc/ghi **bool**. |
| [`disable_gradient_split`](/slides/python-net/vi/aspose.slides.export/svgoptions/disable_gradient_split/) | Vô hiệu hoá việc tách gradient FromCornerX và FromCenter.<br/>            Đọc/ghi **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/vi/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 thiếu khả năng định nghĩa lề cho các marker.<br/>            Engine ghi SVG của Aspose.Slides có giải pháp khắc phục vấn đề này:<br/>            nó cắt phần cuối của đường có mũi tên, vì vậy đường không chồng lên các marker.<br/>            Tùy chọn này tắt hành vi đó.<br/>            Đọc/ghi **bool**. |
| [`default`](/slides/python-net/vi/aspose.slides.export/svgoptions/default/) | Trả về cài đặt mặc định.<br/>            Chỉ đọc [`SVGOptions`](/slides/python-net/vi/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/vi/aspose.slides.export/svgoptions/simple/) | Trả về cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất.<br/>            Chỉ đọc [`SVGOptions`](/slides/python-net/vi/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/vi/aspose.slides.export/svgoptions/wysiwyg/) | Trả về cài đặt cho việc tạo tệp SVG chính xác nhất.<br/>            Chỉ đọc [`SVGOptions`](/slides/python-net/vi/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/vi/aspose.slides.export/svgoptions/jpeg_quality/) | Xác định chất lượng mã hóa JPEG.<br/>            Đọc/ghi **int**. |
| [`shape_formatting_controller`](/slides/python-net/vi/aspose.slides.export/svgoptions/shape_formatting_controller/) | Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng.<br/>            Đọc/ghi [`ISvgShapeFormattingController`](/slides/python-net/vi/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/vi/aspose.slides.export/svgoptions/pictures_compression/) | Biểu diễn mức độ nén hình ảnh |
| [`delete_pictures_cropped_areas`](/slides/python-net/vi/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Cờ boolean chỉ ra nếu các phần đã cắt vẫn là một phần của tài liệu. Nếu true các phần đã cắt sẽ bị xóa,<br/>            nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến một tệp lớn hơn) |
| [`external_fonts_handling`](/slides/python-net/vi/aspose.slides.export/svgoptions/external_fonts_handling/) | Xác định cách xử lý phông chữ được tải từ bên ngoài.<br/>            Đọc/ghi [`SvgExternalFontsHandling`](/slides/python-net/vi/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/vi/aspose.slides.export/svgoptions/disable_font_ligatures/) | Lấy hoặc đặt giá trị cho biết liệu văn bản có được render mà không dùng ligature hay không.<br/>            Khi đặt thành `true`, ligature sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt thành `false`. |


### Xem Thêm
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* lớp [`SVGOptions`](/slides/python-net/vi/aspose.slides.export/svgoptions)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)