---
title: PdfAccessPermissions
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Chứa một tập hợp các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng.
type: docs
url: /vi/com.aspose.slides/pdfaccesspermissions/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Chứa một tập hợp các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng.
## Trường

| Trường | Mô tả |
| --- | --- |
| [None](#None) | Chỉ ra rằng người dùng không có quyền truy cập. |
| [PrintDocument](#PrintDocument) | Chỉ ra liệu người dùng có thể in tài liệu hay không (có thể không ở mức chất lượng cao nhất, tùy thuộc vào việc bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) có được bật hay không). |
| [ModifyContent](#ModifyContent) | Chỉ ra liệu người dùng có thể sửa đổi nội dung của tài liệu bằng các thao tác khác với các thao tác được kiểm soát bởi các bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) hay không. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Chỉ ra liệu người dùng có thể sao chép hoặc trích xuất văn bản và đồ họa từ tài liệu bằng các thao tác khác với thao tác được kiểm soát bởi bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) hay không. |
| [AddOrModifyFields](#AddOrModifyFields) | Chỉ ra liệu người dùng có thể thêm hoặc sửa đổi chú thích văn bản, điền vào các trường biểu mẫu tương tác, và nếu bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) cũng được bật, tạo hoặc sửa đổi các trường biểu mẫu tương tác (bao gồm cả trường chữ ký) hay không. |
| [FillExistingFields](#FillExistingFields) | Chỉ ra liệu người dùng có thể điền vào các trường biểu mẫu tương tác hiện có (bao gồm cả trường chữ ký), ngay cả khi bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) bị tắt hay không. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Chỉ ra liệu người dùng có thể trích xuất văn bản và đồ họa để hỗ trợ khả năng truy cập cho người dùng có khuyết tật hoặc cho các mục đích khác hay không. |
| [AssembleDocument](#AssembleDocument) | Chỉ ra liệu người dùng có thể tập hợp tài liệu (chèn, xoay hoặc xóa trang và tạo dấu trang hoặc hình thu nhỏ), ngay cả khi bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bị tắt hay không. |
| [HighQualityPrint](#HighQualityPrint) | Chỉ ra liệu người dùng có thể in tài liệu thành một dạng đại diện mà từ đó có thể tạo ra bản sao kỹ thuật số chính xác của nội dung PDF hay không. |
### None {#None}
```
public static final int None
```

Chỉ ra rằng người dùng không có quyền truy cập.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Chỉ ra liệu người dùng có thể in tài liệu hay không (có thể không ở mức chất lượng cao nhất, tùy thuộc vào việc bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) có được bật hay không).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Chỉ ra liệu người dùng có thể sửa đổi nội dung của tài liệu bằng các thao tác khác với các thao tác được kiểm soát bởi các bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) hay không.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Chỉ ra liệu người dùng có thể sao chép hoặc trích xuất văn bản và đồ họa từ tài liệu bằng các thao tác khác với thao tác được kiểm soát bởi bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) hay không.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Chỉ ra liệu người dùng có thể thêm hoặc sửa đổi chú thích văn bản, điền vào các trường biểu mẫu tương tác, và nếu bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) cũng được bật, tạo hoặc sửa đổi các trường biểu mẫu tương tác (bao gồm cả trường chữ ký) hay không.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Chỉ ra liệu người dùng có thể điền vào các trường biểu mẫu tương tác hiện có (bao gồm cả trường chữ ký), ngay cả khi bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) bị tắt hay không.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Chỉ ra liệu người dùng có thể trích xuất văn bản và đồ họa để hỗ trợ khả năng truy cập cho người dùng có khuyết tật hoặc cho các mục đích khác hay không.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Chỉ ra liệu người dùng có thể tập hợp tài liệu (chèn, xoay hoặc xóa trang và tạo dấu trang hoặc hình thu nhỏ), ngay cả khi bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bị tắt hay không.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Chỉ ra liệu người dùng có thể in tài liệu thành một dạng đại diện mà từ đó có thể tạo ra bản sao kỹ thuật số chính xác của nội dung PDF hay không. Khi bit này bị tắt (và bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) được bật), việc in sẽ bị giới hạn ở một dạng đại diện mức thấp của giao diện, có thể với chất lượng giảm sút.