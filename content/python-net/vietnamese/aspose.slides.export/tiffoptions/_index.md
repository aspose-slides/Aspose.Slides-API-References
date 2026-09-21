---
title: TiffOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/tiffoptions/
---
## Lớp TiffOptions

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng TIFF.

**Kế thừa:**[`TiffOptions`](/slides/python-net/vi/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu TiffOptions khai báo các thành viên sau:

## Các hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/tiffoptions/__init__/#) | Hàm tạo mặc định. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/tiffoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/tiffoptions/progress_callback/) | Biểu diễn một đối tượng callback để lưu cập nhật tiến độ dưới dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/tiffoptions/default_regular_font/) | Trả về hoặc đặt phông chữ được sử dụng nếu phông chữ nguồn không tìm thấy.<br/>            Đọc-ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/tiffoptions/gradient_style/) | Trả về hoặc đặt kiểu dáng trực quan của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/tiffoptions/skip_java_script_links/) | Xác định có bỏ qua siêu liên kết có lời gọi JavaScript khi lưu bản trình chiếu hay không.<br/>            Đọc/ghi **bool**. Giá trị mặc định là **false**. |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/tiffoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất.<br/>            Chỉ-đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/tiffoptions/show_hidden_slides/) | Xác định liệu tài liệu được tạo có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`image_size`](/slides/python-net/vi/aspose.slides.export/tiffoptions/image_size/) | Xác định kích thước của hình ảnh TIFF được tạo.<br/>            Giá trị mặc định là 0x0, có nghĩa là kích thước hình ảnh sẽ được tính dựa trên kích thước slide của bản trình chiếu.<br/>            Đọc/ghi **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/vi/aspose.slides.export/tiffoptions/dpi_x/) | Xác định độ phân giải ngang tính bằng dot per inch.<br/>            Đọc/ghi **int**. |
| [`dpi_y`](/slides/python-net/vi/aspose.slides.export/tiffoptions/dpi_y/) | Xác định độ phân giải dọc tính bằng dot per inch.<br/>            Đọc/ghi **int**. |
| [`compression_type`](/slides/python-net/vi/aspose.slides.export/tiffoptions/compression_type/) | Xác định loại nén.<br/>            Đọc/ghi [`TiffCompressionTypes`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/vi/aspose.slides.export/tiffoptions/pixel_format/) | Xác định định dạng pixel cho các hình ảnh được tạo.<br/>            Đọc/ghi [`ImagePixelFormat`](/slides/python-net/vi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/tiffoptions/slides_layout_options/) | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/vi/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Xác định thuật toán chuyển ảnh màu sang ảnh đen trắng.<br/>            Tùy chọn này sẽ được áp dụng chỉ nếu [`TiffOptions.compression_type`](/slides/python-net/vi/aspose.slides.export/tiffoptions/compression_type) <br/>            được đặt thành [`TiffCompressionTypes.CCITT4`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes/CCITT4) hoặc [`TiffCompressionTypes.CCITT3`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Đọc/ghi [`BlackWhiteConversionMode`](/slides/python-net/vi/aspose.slides.export/blackwhiteconversionmode).<br/>            Mặc định là [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/vi/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Xem thêm
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* lớp [`TiffOptions`](/slides/python-net/vi/aspose.slides.export/tiffoptions)
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)