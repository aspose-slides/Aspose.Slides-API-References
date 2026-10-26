---
title: aspose.slides.importing
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.importing/
---
## Các lớp

| Lớp | Mô tả |
| :- | :- |
| [`ExcelWorkbookImporter`](/slides/python-net/vi/aspose.slides.importing/excelworkbookimporter/) | Cung cấp chức năng nhập nội dung từ một workbook Excel vào một bài thuyết trình. |
| [`ExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/externalresourceresolver/) | Lớp callback được sử dụng để giải quyết các tài nguyên bên ngoài trong quá trình nhập tài liệu Html, Svg.<br/>            Việc sử dụng resolver này có thể tạo ra lỗ hổng khi tệp HTML hoặc SVG do khách hàng cung cấp làm phần mềm máy chủ truy xuất tệp cục bộ hoặc trên mạng. Hãy sử dụng cẩn thận. Khuyến nghị không chỉ định ExternalResourceResolver (chỉ các đối tượng nhúng sẽ được đọc) hoặc tạo một lớp con nào đó kiểm tra xem uri được chỉ định có hợp lệ hay không. |
| [`HtmlExternalResolver`](/slides/python-net/vi/aspose.slides.importing/htmlexternalresolver/) | Đối tượng callback được sử dụng bởi quy trình nhập HTML để lấy các đối tượng được tham chiếu như hình ảnh.<br/>            Việc sử dụng resolver này có thể gây ra lỗ hổng khi tệp HTML do khách hàng cung cấp làm phần mềm máy chủ truy xuất tệp cục bộ hoặc trên mạng. Hãy sử dụng cẩn thận. Khuyến nghị không chỉ định HtmlExternalResolver (chỉ các đối tượng nhúng sẽ được đọc) hoặc tạo một lớp con nào đó kiểm tra xem uri được chỉ định có hợp lệ hay không. |
| [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver/) | Giao diện callback được sử dụng để giải quyết các tài nguyên bên ngoài trong quá trình nhập tài liệu Html, Svg. |
| [`IHtmlExternalResolver`](/slides/python-net/vi/aspose.slides.importing/ihtmlexternalresolver/) | Giao diện callback được sử dụng bởi quy trình nhập HTML để lấy các đối tượng được tham chiếu như hình ảnh. |
| [`PdfImportOptions`](/slides/python-net/vi/aspose.slides.importing/pdfimportoptions/) | Biểu thị các tùy chọn nhập PDF |