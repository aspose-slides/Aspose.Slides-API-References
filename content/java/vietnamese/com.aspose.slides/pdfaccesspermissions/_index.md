---
title: PdfAccessPermissions
second_title: Tham chiếu API Aspose.Slides cho Java
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
| [None](#None) | Xác định rằng người dùng không có quyền truy cập. |
| [PrintDocument](#PrintDocument) | Xác định liệu người dùng có thể in tài liệu hay không (có thể không ở mức chất lượng cao nhất, tùy thuộc vào việc bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) có được bật hay không). |
| [ModifyContent](#ModifyContent) | Xác định liệu người dùng có thể sửa đổi nội dung của tài liệu bằng các thao tác khác với những thao tác được kiểm soát bởi các bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) hay không. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Xác định liệu người dùng có thể sao chép hoặc trích xuất văn bản và đồ họa từ tài liệu bằng các thao tác khác với thao tác được kiểm soát bởi bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) hay không. |
| [AddOrModifyFields](#AddOrModifyFields) | Xác định liệu người dùng có thể thêm hoặc sửa đổi chú thích văn bản, điền các trường biểu mẫu tương tác, và nếu bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) cũng được bật, tạo hoặc sửa đổi các trường biểu mẫu tương tác (bao gồm các trường chữ ký) hay không. |
| [FillExistingFields](#FillExistingFields) | Xác định liệu người dùng có thể điền các trường biểu mẫu tương tác đã tồn tại (bao gồm các trường chữ ký), ngay cả khi bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) bị xóa. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Xác định liệu người dùng có thể trích xuất văn bản và đồ họa nhằm hỗ trợ khả năng truy cập cho người dùng khuyết tật hoặc cho các mục đích khác. |
| [AssembleDocument](#AssembleDocument) | Xác định liệu người dùng có thể lắp ráp tài liệu (chèn, xoay hoặc xóa các trang và tạo đánh dấu hoặc hình thu nhỏ), ngay cả khi bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bị xóa. |
| [HighQualityPrint](#HighQualityPrint) | Xác định liệu người dùng có thể in tài liệu thành một biểu diễn từ đó có thể tạo ra bản sao kỹ thuật số chính xác của nội dung PDF hay không. |

### None {#None}
```
public static final int None
```

Xác định rằng người dùng không có quyền truy cập.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Xác định liệu người dùng có thể in tài liệu hay không (có thể không ở mức chất lượng cao nhất, tùy thuộc vào việc bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) có được bật hay không).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Xác định liệu người dùng có thể sửa đổi nội dung của tài liệu bằng các thao tác khác với những thao tác được kiểm soát bởi các bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) hay không.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Xác định liệu người dùng có thể sao chép hoặc trích xuất văn bản và đồ họa từ tài liệu bằng các thao tác khác với thao tác được kiểm soát bởi bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) hay không.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Xác định liệu người dùng có thể thêm hoặc sửa đổi chú thích văn bản, điền các trường biểu mẫu tương tác, và nếu bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) cũng được bật, tạo hoặc sửa đổi các trường biểu mẫu tương tác (bao gồm các trường chữ ký) hay không.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Xác định liệu người dùng có thể điền các trường biểu mẫu tương tác đã tồn tại (bao gồm các trường chữ ký), ngay cả khi bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) bị xóa.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Xác định liệu người dùng có thể trích xuất văn bản và đồ họa nhằm hỗ trợ khả năng truy cập cho người dùng khuyết tật hoặc cho các mục đích khác.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Xác định liệu người dùng có thể lắp ráp tài liệu (chèn, xoay hoặc xóa các trang và tạo đánh dấu hoặc hình thu nhỏ), ngay cả khi bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bị xóa.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Xác định liệu người dùng có thể in tài liệu thành một biểu diễn từ đó có thể tạo ra bản sao kỹ thuật số chính xác của nội dung PDF hay không. Khi bit này bị xóa (và bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) được bật), việc in bị giới hạn ở một biểu diễn mức thấp của giao diện, có thể giảm chất lượng.