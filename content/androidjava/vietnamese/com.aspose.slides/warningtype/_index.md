---
title: WarningType
second_title: Aspose.Slides cho Android qua Java API Reference
description: Đại diện cho một loại cảnh báo.
type: docs
url: /vi/com.aspose.slides/warningtype/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Đại diện cho một loại cảnh báo.
## Trường

| Trường | Mô tả |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Đã phát hiện một vấn đề trong tài liệu nguồn khiến khả năng rất cao tài liệu sẽ không thể mở được nếu lưu ở định dạng gốc của nó. |
| [DataLoss](#DataLoss) | Văn bản/biểu đồ/hình ảnh hoặc dữ liệu khác sẽ hoàn toàn thiếu từ cây tài liệu sau khi tải, hoặc từ tài liệu đã tạo sau khi lưu. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Mất định dạng nghiêm trọng. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Mất định dạng nhẹ. |
| [CompatibilityIssue](#CompatibilityIssue) | Đây là vấn đề đã biết sẽ ngăn tài liệu mở được bởi một số trình duyệt người dùng, hoặc các phiên bản trình duyệt trước. |
| [UnexpectedContent](#UnexpectedContent) | Một số nội dung trong tài liệu nguồn không thể nhận dạng được (ví dụ |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Đã phát hiện một vấn đề trong tài liệu nguồn khiến khả năng rất cao tài liệu sẽ không thể mở được nếu lưu ở định dạng gốc của nó.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Văn bản/biểu đồ/hình ảnh hoặc dữ liệu khác sẽ hoàn toàn thiếu từ cây tài liệu sau khi tải, hoặc từ tài liệu đã tạo sau khi lưu.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Mất định dạng nghiêm trọng.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Mất định dạng nhẹ.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Đây là vấn đề đã biết sẽ ngăn tài liệu mở được bởi một số trình duyệt người dùng, hoặc các phiên bản trình duyệt trước.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Một số nội dung trong tài liệu nguồn không thể nhận dạng được (ví dụ không được hỗ trợ), điều này có thể hoặc không thể gây ra vấn đề hoặc dẫn đến mất dữ liệu/định dạng.