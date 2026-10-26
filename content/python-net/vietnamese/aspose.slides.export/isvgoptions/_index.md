---
title: ISVGOptions class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/isvgoptions/
---
## Lớp ISVGOptions

Biểu diễn một tùy chọn SVG.

Kiểu ISVGOptions khai thác các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`vectorize_text`](/slides/python-net/vi/aspose.slides.export/isvgoptions/vectorize_text/) | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không.<br/>            Đọc/ghi **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/vi/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho việc raster hóa metafile.<br/>            Đọc/ghi **int**. |
| [`disable_3d_text`](/slides/python-net/vi/aspose.slides.export/isvgoptions/disable_3d_text/) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không.<br/>            Đọc/ghi **bool**. |
| [`disable_gradient_split`](/slides/python-net/vi/aspose.slides.export/isvgoptions/disable_gradient_split/) | Vô hiệu hoá việc tách gradient FromCornerX và FromCenter.<br/>            Đọc/ghi **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/vi/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 thiếu khả năng định nghĩa lề cho các marker.<br/>            Bộ engine ghi SVG của Aspose.Slides có giải pháp cho vấn đề này:<br/>            nó cắt phần cuối của đường có mũi tên, vì vậy, đường không chồng lên các marker.<br/>            Tùy chọn này tắt hành vi đó.<br/>            Đọc/ghi **bool**. |
| [`jpeg_quality`](/slides/python-net/vi/aspose.slides.export/isvgoptions/jpeg_quality/) | Xác định chất lượng mã hoá JPEG.<br/>            Đọc/ghi **int**. |
| [`shape_formatting_controller`](/slides/python-net/vi/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng.<br/>            Đọc/ghi [`ISvgShapeFormattingController`](/slides/python-net/vi/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/vi/aspose.slides.export/isvgoptions/pictures_compression/) | Biểu diễn mức độ nén hình ảnh<br/>            Đọc/ghi [`ISVGOptions.pictures_compression`](/slides/python-net/vi/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/vi/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Một cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true, các phần đã cắt sẽ bị loại bỏ, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn tới một tệp lớn hơn)<br/>            Đọc/ghi **bool**. |
| [`use_frame_size`](/slides/python-net/vi/aspose.slides.export/isvgoptions/use_frame_size/) | Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định là false. |
| [`use_frame_rotation`](/slides/python-net/vi/aspose.slides.export/isvgoptions/use_frame_rotation/) | Xác định liệu thực hiện quay hình dạng đã chỉ định khi render hay không.<br/>            Đọc/ghi **bool**.<br/>            Giá trị mặc định là true. |
| [`external_fonts_handling`](/slides/python-net/vi/aspose.slides.export/isvgoptions/external_fonts_handling/) | Xác định cách xử lý phông chữ được tải từ bên ngoài.<br/>            Đọc/ghi [`SvgExternalFontsHandling`](/slides/python-net/vi/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/isvgoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất ra.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/vi/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Lấy hoặc đặt giá trị chỉ ra liệu văn bản có được render mà không sử dụng ligatures hay không.<br/>            Khi đặt thành `true`, các ligatures sẽ bị tắt trong output đã render. Mặc định, thuộc tính này được đặt là `false`. |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Xem Thêm
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)