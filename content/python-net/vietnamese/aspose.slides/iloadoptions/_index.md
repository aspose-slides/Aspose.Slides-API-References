---
title: ILoadOptions class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iloadoptions/
---
## ILoadOptions lớp

Cho phép chỉ định các tùy chọn bổ sung (chẳng hạn định dạng hoặc phông chữ mặc định) khi tải một bản trình chiếu.

Kiểu ILoadOptions cung cấp các thành viên sau:

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`load_format`](/slides/python-net/vi/aspose.slides/iloadoptions/load_format/) | Trả về hoặc đặt định dạng của bản trình chiếu để tải.<br/>            Đọc/ghi [`LoadFormat`](/slides/python-net/vi/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/vi/aspose.slides/iloadoptions/default_regular_font/) | Trả về hoặc đặt phông chữ Regular được sử dụng trong trường hợp không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`default_symbol_font`](/slides/python-net/vi/aspose.slides/iloadoptions/default_symbol_font/) | Trả về hoặc đặt phông chữ Symbol được sử dụng trong trường hợp không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`default_asian_font`](/slides/python-net/vi/aspose.slides/iloadoptions/default_asian_font/) | Trả về hoặc đặt phông chữ Asian được sử dụng trong trường hợp không tìm thấy phông nguồn.<br/>            Đọc-ghi **str**. |
| [`password`](/slides/python-net/vi/aspose.slides/iloadoptions/password/) | Lấy hoặc đặt mật khẩu.<br/>            Đọc-ghi **str**. |
| [`only_load_document_properties`](/slides/python-net/vi/aspose.slides/iloadoptions/only_load_document_properties/) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu.<br/>            Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ một tệp bản trình chiếu được mã hóa<br/>            và mật khẩu phải bị bỏ qua.<br/>            Giá trị false có nghĩa là toàn bộ bản trình chiếu được mã hóa phải được tải bằng mật khẩu đúng.<br/>            Nếu bản trình chiếu không được mã hóa thì giá trị thuộc tính luôn bị bỏ qua.<br/>            Nếu các thuộc tính tài liệu của tệp được mã hóa không công khai và giá trị thuộc tính là true thì<br/>            các thuộc tính tài liệu không thể được tải và ngoại lệ sẽ được ném.<br/>            Đọc-ghi **bool**. |
| [`warning_callback`](/slides/python-net/vi/aspose.slides/iloadoptions/warning_callback/) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu việc tải<br/>            quá trình sẽ tiếp tục hay sẽ bị hủy.<br/>            Đọc/ghi [`IWarningCallback`](/slides/python-net/vi/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/vi/aspose.slides/iloadoptions/blob_management_options/) | Đại diện cho các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs),<br/>            chẳng hạn việc sử dụng tệp tạm thời hoặc số byte BLOBs tối đa trong bộ nhớ. Các tùy chọn này nhằm thiết lập<br/>            tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.<br/>            Một Binary Large Object (BLOB) là dữ liệu nhị phân lưu trữ dưới dạng một thực thể duy nhất - tức là BLOB có thể <br/>            là âm thanh, video hoặc chính bản trình chiếu. |
| [`document_level_font_sources`](/slides/python-net/vi/aspose.slides/iloadoptions/document_level_font_sources/) | Xác định các nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu.<br/>            Các phông chữ này có sẵn cho bản trình chiếu trong suốt thời gian tồn tại và không được chia sẻ với các bản trình chiếu khác. |
| [`interruption_token`](/slides/python-net/vi/aspose.slides/iloadoptions/interruption_token/) | Mã token để giám sát các yêu cầu ngắt.<br/>            <br/>            Token này quản lý toàn bộ vòng đời của instance [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). Bất kỳ hoạt động chạy lâu nào, chẳng hạn tải hoặc lưu bản trình chiếu, sẽ bị ngắt bằng cách gọi phương thức [`IInterruptionTokenSource.interrupt`](/slides/python-net/vi/aspose.slides/iinterruptiontokensource/interrupt) của [`IInterruptionTokenSource`](/slides/python-net/vi/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/vi/aspose.slides/iloadoptions/resource_loading_callback/) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài.<br/>            Đọc/ghi [`IResourceLoadingCallback`](/slides/python-net/vi/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/vi/aspose.slides/iloadoptions/spreadsheet_options/) | Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bảng tính bổ sung. |
| [`default_text_language`](/slides/python-net/vi/aspose.slides/iloadoptions/default_text_language/) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu.<br/>             Đọc/ghi **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/vi/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Xác định liệu Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không.<br/>            <br/>Các loại đối tượng nhị phân nhúng:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/vi/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/vi/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Đọc/ghi **bool**. |


### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)