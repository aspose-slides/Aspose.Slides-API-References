---
title: PdfAccessPermissions enumeration
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeration

Chứa một tập hợp các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền truy cập người dùng.

Kiểu PdfAccessPermissions cung cấp các thành viên sau:

## Fields

| Trường | Mô tả |
| :- | :- |
| NONE | Xác định rằng người dùng không có quyền truy cập. |
| PRINT_DOCUMENT | Xác định xem người dùng có thể in tài liệu hay không (có thể không ở mức chất lượng cao nhất, phụ thuộc vào việc <br/>            bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) cũng được đặt hay không). |
| MODIFY_CONTENT | Xác định xem người dùng có thể sửa đổi nội dung của tài liệu bằng các thao tác khác với những thao tác được kiểm soát<br/>            bởi các bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Xác định xem người dùng có thể sao chép hoặc trích xuất văn bản và đồ họa từ tài liệu bằng các thao tác <br/>            khác với thao tác được kiểm soát bởi bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Xác định xem người dùng có thể thêm hoặc sửa đổi chú thích văn bản, điền vào các trường biểu mẫu tương tác, và, nếu bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) cũng được đặt, tạo hoặc sửa đổi các trường biểu mẫu tương tác (bao gồm các trường chữ ký <br/>            ). |
| FILL_EXISTING_FIELDS | Xác định xem người dùng có thể điền vào các trường biểu mẫu tương tác hiện có (bao gồm các trường chữ ký), ngay cả khi<br/>            bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) không được đặt. |
| EXTRACT_TEXT_AND_GRAPHICS | Xác định xem người dùng có thể trích xuất văn bản và đồ họa nhằm hỗ trợ khả năng truy cập cho người dùng khuyết tật<br/>            hoặc cho các mục đích khác. |
| ASSEMBLE_DOCUMENT | Xác định xem người dùng có thể tổ chức lại tài liệu (chèn, xoay hoặc xóa trang và tạo dấu trang hoặc<br/>            hình thu nhỏ), ngay cả khi bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) không được đặt. |
| HIGH_QUALITY_PRINT | Xác định xem người dùng có thể in tài liệu thành một biểu diễn mà từ đó có thể tạo ra bản sao kỹ thuật số chính xác của<br/>            nội dung PDF. Khi bit này không được đặt (và bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/vi/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) được đặt),<br/>            việc in sẽ bị giới hạn ở một biểu diễn cấp thấp của giao diện, có thể với chất lượng giảm sút. |

### Xem Thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)