---
title: IPdfOptions class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/ipdfoptions/
---
## IPdfOptions lớp

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Pdf.

Kiểu IPdfOptions bật các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/text_compression/) | Chỉ định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu.<br/>            Đọc/ghi [`PdfTextCompression`](/slides/python-net/vi/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Cho biết có nên tự động chọn nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không.<br/>            Nếu đặt thành **bool**.true, đối với mỗi hình ảnh trong bản trình chiếu, thuật toán nén thích hợp nhất sẽ được chọn, dẫn đến kích thước PDF kết quả nhỏ hơn.<br/>            Việc chọn tỷ lệ nén hình ảnh tốt nhất tốn tính toán cao và tiêu tốn thêm RAM, và tùy chọn này mặc định là **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Đặt true để nhúng phông chữ TrueType cho các ký tự ASCII 32-127.<br/>            Phông chữ cho các mã ký tự lớn hơn 127 luôn được nhúng.<br/>            Đọc/ghi **bool**. |
| [`show_hidden_slides`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Chỉ định tài liệu được tạo có nên bao gồm các slide ẩn hay không.<br/>            Mặc định là `false`. |
| [`additional_common_font_families`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Trả về hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides sẽ coi là chung.<br/>            Đọc/ghi **str**[]. |
| [`embed_full_fonts`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Xác định có nên nhúng tất cả ký tự của phông chữ hoặc chỉ một tập con được sử dụng.<br/>            Đọc/ghi **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Cho biết liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu chữ đậm hay không.<br/>            Cách tiếp cận này có thể cải thiện chất lượng văn bản trong PDF kết quả cho một số phông chữ nhất định.<br/>            Đọc/ghi **bool**. |
| [`jpeg_quality`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/jpeg_quality/) | Trả về hoặc đặt giá trị xác định chất lượng của các ảnh JPEG trong tài liệu PDF.<br/>            Đọc/ghi **int**. |
| [`compliance`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/compliance/) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo.<br/>            Đọc/ghi [`PdfCompliance`](/slides/python-net/vi/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/password/) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF.<br/>            Đọc/ghi **str**. |
| [`access_permissions`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/access_permissions/) | Chứa một tập hợp các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng.<br/>            Xem [`PdfAccessPermissions`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Đặt true để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành hình ảnh PNG.<br/>            Đọc/ghi **bool**. |
| [`sufficient_resolution`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Trả về hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF.<br/>            <br/>Thuộc tính ảnh hưởng đến kích thước tệp, thời gian xuất và chất lượng hình ảnh.<br/><br/><br/>Giá trị mặc định là **96** .<br/><br/><br/>            Đọc/ghi **float**. |
| [`draw_slides_frame`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Đặt true để vẽ khung đen quanh mỗi slide.<br/>             Đọc/ghi **bool**. |
| [`slides_layout_options`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/slides_layout_options/) | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](/slides/python-net/vi/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/image_transparent_color/) | Lấy hoặc đặt màu trong suốt của hình ảnh. |
| [`apply_image_transparent`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu `true`. |
| [`ink_options`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/ink_options/) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất.<br/>            Chỉ đọc [`IInkOptions`](/slides/python-net/vi/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/include_ole_data/) | Đặt true để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả.<br/>            Đọc/ghi **bool**. |
| [`warning_callback`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/vi/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)