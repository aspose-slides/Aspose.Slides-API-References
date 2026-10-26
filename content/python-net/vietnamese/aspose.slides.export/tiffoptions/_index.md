---
title: TiffOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/tiffoptions/
---
## TiffOptions lớp

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng TIFF.

**Kế thừa:**[`TiffOptions`](/slides/python-net/vi/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu TiffOptions cung cấp các thành viên sau:

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/tiffoptions/__init__/#) | Hàm khởi tạo mặc định. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/tiffoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/tiffoptions/progress_callback/) | Đại diện cho một đối tượng callback để lưu cập nhật tiến độ dưới dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/tiffoptions/default_regular_font/) | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn.<br/>            Đọc/ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/tiffoptions/gradient_style/) | Trả về hoặc đặt kiểu hiển thị của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/tiffoptions/skip_java_script_links/) | Xác định xem có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình chiếu hay không.<br/>            Đọc/ghi **bool**. Giá trị mặc định là **false**. |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/tiffoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu được xuất.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/tiffoptions/show_hidden_slides/) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`image_size`](/slides/python-net/vi/aspose.slides.export/tiffoptions/image_size/) | Xác định kích thước của ảnh TIFF được tạo.<br/>            Giá trị mặc định là 0x0, có nghĩa là kích thước ảnh sẽ được tính dựa trên giá trị kích thước slide của bản trình chiếu.<br/>            Đọc/ghi [`Size`](/slides/python-net/vi/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/vi/aspose.slides.export/tiffoptions/dpi_x/) | Xác định độ phân giải theo chiều ngang tính bằng dot per inch.<br/>            Đọc/ghi **int**. |
| [`dpi_y`](/slides/python-net/vi/aspose.slides.export/tiffoptions/dpi_y/) | Xác định độ phân giải theo chiều dọc tính bằng dot per inch.<br/>            Đọc/ghi **int**. |
| [`compression_type`](/slides/python-net/vi/aspose.slides.export/tiffoptions/compression_type/) | Xác định kiểu nén.<br/>            Đọc/ghi [`TiffCompressionTypes`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/vi/aspose.slides.export/tiffoptions/pixel_format/) | Xác định định dạng pixel cho các ảnh được tạo.<br/>            Đọc/ghi [`ImagePixelFormat`](/slides/python-net/vi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/tiffoptions/slides_layout_options/) | Lấy hoặc đặt chế độ mà các slide được sắp xếp trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/vi/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Xác định thuật toán chuyển đổi ảnh màu thành ảnh đen trắng.<br/>            Tùy chọn này chỉ được áp dụng nếu [`TiffOptions.compression_type`](/slides/python-net/vi/aspose.slides.export/tiffoptions/compression_type) <br/>
            được đặt thành [`TiffCompressionTypes.CCITT4`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes/CCITT4) hoặc [`TiffCompressionTypes.CCITT3`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>
            Đọc/ghi [`BlackWhiteConversionMode`](/slides/python-net/vi/aspose.slides.export/blackwhiteconversionmode).<br/>
            Mặc định là [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/vi/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### Xem thêm
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* lớp [`TiffOptions`](/slides/python-net/vi/aspose.slides.export/tiffoptions)
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)