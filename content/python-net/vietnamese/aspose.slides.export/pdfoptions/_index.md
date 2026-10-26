---
title: PdfOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/pdfoptions/
---
## Lớp PdfOptions

Cung cấp các tùy chọn kiểm soát cách một bài thuyết trình được lưu dưới định dạng Pdf.

**Kế thừa:**[`PdfOptions`](/slides/python-net/vi/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)

Kiểu PdfOptions cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/pdfoptions/__init__/#) | Hàm tạo mặc định. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/pdfoptions/warning_callback/) | Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/pdfoptions/progress_callback/) | Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm.<br/>            Xem [`IProgressCallback`](/slides/python-net/vi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/pdfoptions/default_regular_font/) | Trả về hoặc thiết lập phông chữ được sử dụng khi không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/pdfoptions/gradient_style/) | Trả về hoặc thiết lập kiểu dáng trực quan của gradient.<br/>            Đọc/ghi [`GradientStyle`](/slides/python-net/vi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/pdfoptions/skip_java_script_links/) | Chỉ định có bỏ qua các siêu liên kết có lệnh JavaScript khi lưu bài thuyết trình hay không. <br/>            Đọc/ghi **bool**. Giá trị mặc định là **false**. |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/pdfoptions/slides_layout_options/) | Lấy hoặc thiết lập chế độ sắp xếp các slide trên trang khi xuất bài thuyết trình [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/pdfoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/pdfoptions/show_hidden_slides/) | Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`text_compression`](/slides/python-net/vi/aspose.slides.export/pdfoptions/text_compression/) | Chỉ định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu.<br/>            Đọc/ghi [`PdfTextCompression`](/slides/python-net/vi/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/vi/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Cho biết có nên tự động chọn chế độ nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không <br/>            Nếu được đặt thành **bool**.true, đối với mọi hình ảnh trong bài thuyết trình, thuật toán nén phù hợp nhất sẽ được chọn, dẫn đến kích thước PDF kết quả nhỏ hơn. <br/>            Việc chọn tỷ lệ nén hình ảnh tốt nhất tốn nhiều tính toán và tiêu tốn thêm RAM, và tùy chọn này mặc định là **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/vi/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Xác định liệu Aspose.Slides có nhúng các phông chữ phổ biến cho văn bản ASCII (phạm vi mã 33..127) hay không.<br/>            Các phông chữ cho các mã ký tự lớn hơn 127 luôn được nhúng.<br/>            Danh sách phông chữ phổ biến bao gồm 14 phông chữ cơ bản của PDF và các phông chữ do người dùng chỉ định thêm.<br/>            Đọc/ghi **bool**. |
| [`additional_common_font_families`](/slides/python-net/vi/aspose.slides.export/pdfoptions/additional_common_font_families/) | Trả về hoặc thiết lập một mảng các tên họ phông chữ do người dùng định nghĩa mà Aspose.Slides nên xem là phổ biến.<br/>            Đọc/ghi **str**[]. |
| [`embed_full_fonts`](/slides/python-net/vi/aspose.slides.export/pdfoptions/embed_full_fonts/) | Xác định liệu toàn bộ ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng.<br/>            Đọc/ghi **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/vi/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Cho biết liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu dáng đậm không.<br/>            Cách tiếp cận này có thể cải thiện chất lượng văn bản trong PDF kết quả đối với một số phông chữ nhất định.<br/>            Đọc/ghi **bool**. |
| [`jpeg_quality`](/slides/python-net/vi/aspose.slides.export/pdfoptions/jpeg_quality/) | Trả về hoặc thiết lập giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF.<br/>            Đọc/ghi **int**. |
| [`compliance`](/slides/python-net/vi/aspose.slides.export/pdfoptions/compliance/) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo.<br/>            Đọc/ghi [`PdfCompliance`](/slides/python-net/vi/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/vi/aspose.slides.export/pdfoptions/password/) | Thiết lập mật khẩu người dùng để bảo vệ tài liệu PDF. <br/>            Đọc/ghi **str**. |
| [`access_permissions`](/slides/python-net/vi/aspose.slides.export/pdfoptions/access_permissions/) | Chứa một tập hợp các cờ chỉ định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng.<br/>            Xem [`PdfAccessPermissions`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/vi/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Đặt true để chuyển đổi tất cả các metafile được sử dụng trong bài thuyết trình sang ảnh PNG.<br/>            Đọc/ghi **bool**. |
| [`sufficient_resolution`](/slides/python-net/vi/aspose.slides.export/pdfoptions/sufficient_resolution/) | Trả về hoặc thiết lập giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF.<br/>            <br/>Thuộc tính này ảnh hưởng đến kích thước tệp, thời gian xuất và chất lượng hình ảnh.<br/><br/><br/>Giá trị mặc định là **96** .<br/><br/><br/>            Đọc/ghi **float**. |
| [`draw_slides_frame`](/slides/python-net/vi/aspose.slides.export/pdfoptions/draw_slides_frame/) | Đặt true để vẽ khung đen quanh mỗi slide.<br/>             Đọc/ghi **bool**. |
| [`image_transparent_color`](/slides/python-net/vi/aspose.slides.export/pdfoptions/image_transparent_color/) | Lấy hoặc thiết lập màu trong suốt của hình ảnh. |
| [`apply_image_transparent`](/slides/python-net/vi/aspose.slides.export/pdfoptions/apply_image_transparent/) | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu `true`. |
| [`include_ole_data`](/slides/python-net/vi/aspose.slides.export/pdfoptions/include_ole_data/) | Đặt true để chuyển đổi tất cả dữ liệu OLE từ bài thuyết trình thành các tệp nhúng trong PDF kết quả.<br/>            Đọc/ghi **bool**. |

### Xem thêm
* lớp [`PdfOptions`](/slides/python-net/vi/aspose.slides.export/pdfoptions)
* lớp [`SaveOptions`](/slides/python-net/vi/aspose.slides.export/saveoptions)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)