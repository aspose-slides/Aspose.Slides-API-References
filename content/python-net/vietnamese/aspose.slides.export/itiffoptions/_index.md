---
title: ITiffOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/itiffoptions/
---
## ITiffOptions lớp

Provides options that control how a presentation is saved in TIFF format.

The ITiffOptions type exposes the following members:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`image_size`](/slides/python-net/vi/aspose.slides.export/itiffoptions/image_size/) | Xác định kích thước của hình ảnh TIFF được tạo.<br/>            Giá trị mặc định là 0x0, có nghĩa là kích thước hình ảnh được tạo sẽ được tính dựa trên giá trị kích thước slide của bản trình chiếu.<br/>            Đọc/ghi [`Size`](/slides/python-net/vi/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/vi/aspose.slides.export/itiffoptions/dpi_x/) | Xác định độ phân giải ngang tính bằng điểm trên inch.<br/>            Đọc/ghi **int**. |
| [`dpi_y`](/slides/python-net/vi/aspose.slides.export/itiffoptions/dpi_y/) | Xác định độ phân giải dọc tính bằng điểm trên inch.<br/>            Đọc/ghi **int**. |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/itiffoptions/show_hidden_slides/) | Xác định liệu tài liệu được tạo có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`compression_type`](/slides/python-net/vi/aspose.slides.export/itiffoptions/compression_type/) | Xác định loại nén.<br/>            Đọc/ghi [`TiffCompressionTypes`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/vi/aspose.slides.export/itiffoptions/pixel_format/) | Xác định định dạng pixel cho các hình ảnh được tạo.<br/>            Đọc/ghi [`ImagePixelFormat`](/slides/python-net/vi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/itiffoptions/slides_layout_options/) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/vi/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Xác định thuật toán chuyển đổi hình ảnh màu sang hình ảnh đen trắng.<br/>            Tùy chọn này sẽ được áp dụng chỉ nếu [`ITiffOptions.compression_type`](/slides/python-net/vi/aspose.slides.export/itiffoptions/compression_type) <br/>            được đặt thành [`TiffCompressionTypes.CCITT4`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes/CCITT4) hoặc [`TiffCompressionTypes.CCITT3`](/slides/python-net/vi/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Đọc/ghi [`BlackWhiteConversionMode`](/slides/python-net/vi/aspose.slides.export/blackwhiteconversionmode).<br/>            Mặc định là [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/vi/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/itiffoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)