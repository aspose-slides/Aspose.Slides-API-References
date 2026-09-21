---
title: HtmlOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/htmloptions/
---
## HtmlOptions lớp

Đại diện cho các tùy chọn xuất HTML.

**Kế thừa:**[`HtmlOptions`](/slides/python-net/vi/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu HtmlOptions cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/vi/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Creates a new HtmlOptions object specifiing callback. |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/htmloptions/__init__/#) | Creates a new HtmlOptions object for saving into single HTML file. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/htmloptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay sẽ bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/htmloptions/progress_callback/) | Đại diện cho một đối tượng callback để lưu cập nhật tiến độ dưới dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/htmloptions/default_regular_font/) | Trả về hoặc đặt phông chữ được sử dụng nếu không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/htmloptions/gradient_style/) | Trả về hoặc đặt kiểu hiển thị của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/htmloptions/skip_java_script_links/) | Xác định xem có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không.<br/>            Đọc/ghi **bool**. Giá trị mặc định là **false**. |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/htmloptions/slides_layout_options/) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình bày [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/htmloptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/htmloptions/show_hidden_slides/) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`html_formatter`](/slides/python-net/vi/aspose.slides.export/htmloptions/html_formatter/) | Trả về hoặc đặt mẫu HTML.<br/>            Đọc/ghi [`IHtmlFormatter`](/slides/python-net/vi/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/vi/aspose.slides.export/htmloptions/disable_font_ligatures/) | Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligatures hay không.<br/>            Khi đặt thành `true`, ligatures sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là `false`. |
| [`slide_image_format`](/slides/python-net/vi/aspose.slides.export/htmloptions/slide_image_format/) | Trả về hoặc đặt các tùy chọn định dạng ảnh slide.<br/>            Đọc/ghi [`ISlideImageFormat`](/slides/python-net/vi/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/vi/aspose.slides.export/htmloptions/jpeg_quality/) | Trả về hoặc đặt giá trị xác định chất lượng của các ảnh JPEG trong tài liệu PDF.<br/>            Đọc/ghi **int**. |
| [`pictures_compression`](/slides/python-net/vi/aspose.slides.export/htmloptions/pictures_compression/) | Đại diện cho mức nén hình ảnh |
| [`delete_pictures_cropped_areas`](/slides/python-net/vi/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Một cờ boolean cho biết liệu các phần đã cắt vẫn còn là một phần của tài liệu hay không. Nếu true, các phần đã cắt sẽ bị loại bỏ, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tập tin lớn hơn) |
| [`svg_responsive_layout`](/slides/python-net/vi/aspose.slides.export/htmloptions/svg_responsive_layout/) | True để loại bỏ các thuộc tính width và height khỏi container svg - sẽ làm bố cục phản hồi. False - ngược lại.<br/>            Đọc/ghi **bool**. |


### Xem thêm
* lớp [`HtmlOptions`](/slides/python-net/vi/aspose.slides.export/htmloptions)
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)