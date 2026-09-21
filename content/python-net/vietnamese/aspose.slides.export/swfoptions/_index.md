---
title: SwfOptions class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.export/swfoptions/
---
## SwfOptions lớp

Cung cấp các tùy chọn kiểm soát cách một bài thuyết trình được lưu ở định dạng Swf.

**Kế thừa:**[`SwfOptions`](/slides/python-net/vi/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu SwfOptions cung cấp các thành viên sau:

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/swfoptions/__init__/#) | Hàm khởi tạo mặc định. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/swfoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy bỏ.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/swfoptions/progress_callback/) | Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/swfoptions/default_regular_font/) | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/swfoptions/gradient_style/) | Trả về hoặc đặt kiểu dáng trực quan của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/swfoptions/skip_java_script_links/) | Chỉ định liệu có bỏ qua các liên kết siêu văn bản có lời gọi JavaScript khi lưu bài thuyết trình hay không. <br/>            Đọc/ghi **bool**. Giá trị mặc định là **false** . |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_hidden_slides/) | Chỉ định liệu tài liệu đã tạo có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`compressed`](/slides/python-net/vi/aspose.slides.export/swfoptions/compressed/) | Chỉ định liệu tài liệu SWF đã tạo có nên được nén hay không.<br/>            Mặc định là `true`. |
| [`viewer_included`](/slides/python-net/vi/aspose.slides.export/swfoptions/viewer_included/) | Chỉ định liệu tài liệu SWF đã tạo có bao gồm trình xem tài liệu tích hợp hay không.<br/>            Mặc định là `true`. |
| [`show_page_border`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_page_border/) | Chỉ định liệu viền quanh các trang có được hiển thị hay không. Mặc định là true. |
| [`show_full_screen`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_full_screen/) | Hiển thị/ẩn nút toàn màn hình. Có thể được ghi đè trong flashvars. Mặc định là true. |
| [`show_page_stepper`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_page_stepper/) | Hiển thị/ẩn bộ điều khiển trang. Có thể được ghi đè trong flashvars. Mặc định là true. |
| [`show_search`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_search/) | Hiển thị/ẩn phần tìm kiếm. Có thể được ghi đè trong flashvars. Mặc định là true. |
| [`show_top_pane`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_top_pane/) | Hiển thị/ẩn toàn bộ khung trên. Có thể được ghi đè trong flashvars. Mặc định là true. |
| [`show_bottom_pane`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_bottom_pane/) | Hiển thị/ẩn khung dưới. Có thể được ghi đè trong flashvars. Mặc định là true. |
| [`show_left_pane`](/slides/python-net/vi/aspose.slides.export/swfoptions/show_left_pane/) | Hiển thị/ẩn khung trái. Có thể được ghi đè trong flashvars. Mặc định là true. |
| [`start_open_left_pane`](/slides/python-net/vi/aspose.slides.export/swfoptions/start_open_left_pane/) | Bắt đầu với khung trái mở. Có thể được ghi đè trong flashvars. Mặc định là false. |
| [`enable_context_menu`](/slides/python-net/vi/aspose.slides.export/swfoptions/enable_context_menu/) | Bật/tắt menu ngữ cảnh. Mặc định là true. |
| [`logo_image_bytes`](/slides/python-net/vi/aspose.slides.export/swfoptions/logo_image_bytes/) | Hình ảnh sẽ được hiển thị làm logo ở góc phải trên của trình xem.<br/>            Hình ảnh nên là PNG kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng. |
| [`logo_link`](/slides/python-net/vi/aspose.slides.export/swfoptions/logo_link/) | Lấy hoặc đặt địa chỉ liên kết đầy đủ cho logo.<br/>            Chỉ có hiệu lực nếu một [`SwfOptions.logo_image_bytes`](/slides/python-net/vi/aspose.slides.export/swfoptions/logo_image_bytes) được chỉ định. |
| [`jpeg_quality`](/slides/python-net/vi/aspose.slides.export/swfoptions/jpeg_quality/) | Chỉ định chất lượng của ảnh JPEG.<br/>            Mặc định là 95. |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/swfoptions/slides_layout_options/) | Lấy hoặc đặt chế độ sắp xếp slide trên trang khi xuất bài thuyết trình [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). <br/>            Thuộc tính này không hỗ trợ gán đối tượng loại [`HandoutLayoutingOptions`](/slides/python-net/vi/aspose.slides.export/handoutlayoutingoptions) |

### Xem thêm
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* lớp [`SwfOptions`](/slides/python-net/vi/aspose.slides.export/swfoptions)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)