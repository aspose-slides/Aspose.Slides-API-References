---
title: MarkdownSaveOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions lớp

Đại diện cho các tùy chọn kiểm soát cách bản trình chiếu được lưu dưới dạng markdown.

**Kế thừa:**[`MarkdownSaveOptions`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu MarkdownSaveOptions cung cấp các thành viên sau:

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/__init__/#) | Hàm khởi tạo. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay sẽ bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/progress_callback/) | Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn.<br/>            Đọc/ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/gradient_style/) | Trả về hoặc đặt kiểu hiển thị của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Xác định có bỏ qua các liên kết với lời gọi JavaScript khi lưu bản trình chiếu hay không.<br/>            Đọc/ghi **bool**. Giá trị mặc định là **false** . |
| [`export_type`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/export_type/) | Xác định đặc tả markdown để chuyển đổi bản trình chiếu.<br/>            Mặc định là `TextOnly`. |
| [`base_path`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/base_path/) | Xác định đường dẫn cơ sở nơi tài liệu kèm tài nguyên sẽ được lưu.<br/>            Mặc định là thư mục hiện tại của ứng dụng. |
| [`images_save_folder_name`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Xác định tên thư mục để lưu hình ảnh.<br/>            Mặc định là `Images`. |
| [`new_line_type`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/new_line_type/) | Xác định liệu tài liệu tạo ra có sử dụng ký tự xuống dòng \\r (Macintosh), \\n (Unix) hoặc \\r\\n (Windows) hay không.<br/>            Mặc định là `Unix`. |
| [`show_comments`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/show_comments/) | Xác định liệu tài liệu tạo ra có hiển thị chú thích hay không.<br/>            Mặc định là `false`. |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Xác định liệu tài liệu tạo ra có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`show_slide_number`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Xác định liệu tài liệu tạo ra có hiển thị số của mỗi slide hay không.<br/>            Mặc định là `false`. |
| [`flavor`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/flavor/) | Xác định đặc tả markdown để chuyển đổi bản trình chiếu.<br/>            Mặc định là `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Lấy hoặc đặt chuỗi định dạng dùng cho tiêu đề số slide trong đầu ra Markdown.<br/>            Định dạng phải bao gồm chỗ giữ chỗ \"{0}\", sẽ được thay thế bằng chỉ số slide khi xuất.<br/>            Ví dụ: \"# Slide {0}\" sẽ tạo ra \"# Slide 1\", \"# Slide 2\", v.v. |
| [`handle_repeated_spaces`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Nếu đặt là `true`, sẽ loại bỏ các dòng trống hoặc chỉ có khoảng trắng khỏi đầu ra Markdown cuối cùng.<br/>            Mặc định là `false`. |

### Xem thêm
* lớp [`MarkdownSaveOptions`](/slides/python-net/vi/aspose.slides.export/markdownsaveoptions)
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)