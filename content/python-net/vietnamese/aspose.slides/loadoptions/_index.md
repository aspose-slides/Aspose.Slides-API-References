---
title: LoadOptions class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/loadoptions/
---
## LoadOptions lớp

Cho phép chỉ định các tùy chọn bổ sung (chẳng hạn như định dạng hoặc phông chữ mặc định) khi tải một bản trình bày.

Kiểu LoadOptions cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__(self, load_format)`](/slides/python-net/vi/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`load_format`](/slides/python-net/vi/aspose.slides/loadoptions/load_format/) | Trả về hoặc đặt định dạng của bản trình bày để tải.<br/>            Đọc/ghi [`LoadFormat`](/slides/python-net/vi/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides/loadoptions/default_regular_font/) | Trả về hoặc đặt phông Regular được sử dụng khi không tìm thấy phông nguồn.<br/>            Đọc/ghi **str**. |
| [`default_symbol_font`](/slides/python-net/vi/aspose.slides/loadoptions/default_symbol_font/) | Trả về hoặc đặt phông Symbol được sử dụng khi không tìm thấy phông nguồn.<br/>            Đọc/ghi **str**. |
| [`default_asian_font`](/slides/python-net/vi/aspose.slides/loadoptions/default_asian_font/) | Trả về hoặc đặt phông Asian được sử dụng khi không tìm thấy phông nguồn.<br/>            Đọc/ghi **str**. |
| [`password`](/slides/python-net/vi/aspose.slides/loadoptions/password/) | Lấy hoặc đặt mật khẩu.<br/>            Đọc/ghi **str**. |
| [`only_load_document_properties`](/slides/python-net/vi/aspose.slides/loadoptions/only_load_document_properties/) | Thuộc tính này có ý nghĩa nếu tệp bản trình bày được bảo vệ bằng mật khẩu.<br/>            Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ tệp bản trình bày được mã hóa và mật khẩu phải bị bỏ qua.<br/>            Giá trị false có nghĩa là toàn bộ bản trình bày được mã hóa phải được tải bằng mật khẩu đúng.<br/>            Nếu bản trình bày không được mã hóa thì giá trị thuộc tính luôn bị bỏ qua.<br/>            Nếu các thuộc tính tài liệu của tệp được mã hóa không công khai và giá trị thuộc tính là true thì<br/>            không thể tải các thuộc tính tài liệu và sẽ ném ra ngoại lệ.<br/>            Đọc/ghi **bool**. |
| [`warning_callback`](/slides/python-net/vi/aspose.slides/loadoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải <br/>            có tiếp tục hay sẽ bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/vi/aspose.slides/loadoptions/blob_management_options/) | Đại diện cho các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs),<br/>            chẳng hạn như việc sử dụng tệp tạm thời hoặc giới hạn số byte BLOBs tối đa trong bộ nhớ. Những tùy chọn này nhằm thiết lập<br/>            tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.<br/>            Binary Large Object (BLOB) là dữ liệu nhị phân được lưu dưới dạng một thực thể duy nhất - tức là BLOB có thể <br/>            là âm thanh, video hoặc bản trình bày tự nó. |
| [`document_level_font_sources`](/slides/python-net/vi/aspose.slides/loadoptions/document_level_font_sources/) | Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bản trình bày.<br/>            Các phông chữ này có sẵn cho bản trình bày trong suốt thời gian sống của nó và không được chia sẻ với các bản trình bày khác |
| [`interruption_token`](/slides/python-net/vi/aspose.slides/loadoptions/interruption_token/) | Token để giám sát các yêu cầu ngắt.<br/>            <br/>            Token này quản lý toàn bộ vòng đời của thể hiện [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). Bất kỳ hoạt động dài nào, chẳng hạn như tải <br/>            hoặc lưu bản trình bày, sẽ bị ngắt bằng cách gọi phương thức [`InterruptionTokenSource.interrupt`](/slides/python-net/vi/aspose.slides/interruptiontokensource/interrupt) của <br/>            [`InterruptionTokenSource`](/slides/python-net/vi/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/vi/aspose.slides/loadoptions/resource_loading_callback/) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài.<br/>            Đọc/ghi [`IResourceLoadingCallback`](/slides/python-net/vi/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/vi/aspose.slides/loadoptions/spreadsheet_options/) | Lấy các tùy chọn cho bảng tính. Ví dụ, những tùy chọn này ảnh hưởng đến việc tính công thức cho biểu đồ. |
| [`default_text_language`](/slides/python-net/vi/aspose.slides/loadoptions/default_text_language/) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình bày.<br/>             Đọc/ghi **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/vi/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Xác định xem Aspose.Slides có sẽ xóa tất cả các đối tượng nhị phân được nhúng khi tải bản trình bày hay không.<br/>            <br/>Các loại đối tượng nhị phân được nhúng:<br/><br/><br/>* Dự án VBA [`IPresentation.vba_project`](/slides/python-net/vi/aspose.slides/ipresentation/vba_project)<br/>* Dữ liệu nhúng OLE Object [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* Dữ liệu nhị phân ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/vi/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Đọc/ghi **bool**. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)