---
title: IOverridableText
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho văn bản có thể ghi đè cho biểu đồ.
type: docs
url: /vi/com.aspose.slides/ioverridabletext/
---
**Tất cả giao diện đã triển khai:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Đại diện cho văn bản có thể ghi đè cho biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Có thể chứa văn bản được định dạng phong phú. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Khởi tạo TextFrameForOverriding với văn bản trong tham số "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Có thể chứa văn bản được định dạng phong phú. Nếu thuộc tính này không null thì giá trị văn bản định dạng này sẽ ghi đè lên văn bản được tạo tự động. Văn bản được tạo tự động là một thuộc tính ngầm của nhãn dữ liệu, nhãn đơn vị hiển thị của trục giá trị, tiêu đề trục, tiêu đề biểu đồ, nhãn của đường xu hướng. Văn bản được tạo tự động được định dạng bằng thuộc tính IFormattedTextContainer.TextFormat. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Khởi tạo TextFrameForOverriding với văn bản trong tham số "text". Nếu TextFrameForOverriding đã được khởi tạo rồi thì chỉ thay đổi văn bản của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cho một TextFrameForOverriding mới. |

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe) - Khung văn bản [ITextFrame](../../com.aspose.slides/itextframe)