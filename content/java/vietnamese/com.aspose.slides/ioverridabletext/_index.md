---
title: IOverridableText
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn văn bản có thể ghi đè cho biểu đồ.
type: docs
url: /vi/com.aspose.slides/ioverridabletext/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Biểu diễn văn bản có thể ghi đè cho biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Có thể chứa văn bản được định dạng phong phú. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Khởi tạo TextFrameForOverriding với văn bản trong tham số "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Có thể chứa văn bản được định dạng phong phú. Nếu thuộc tính này không null thì giá trị văn bản định dạng này sẽ ghi đè văn bản tự động tạo. Văn bản tự động tạo là thuộc tính ngầm của nhãn dữ liệu, nhãn đơn vị hiển thị của trục giá trị, tiêu đề trục, tiêu đề biểu đồ, nhãn của đường xu hướng. Văn bản tự động tạo được định dạng bằng thuộc tính IFormattedTextContainer.TextFormat. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Khởi tạo TextFrameForOverriding với văn bản trong tham số "text". Nếu TextFrameForOverriding đã được khởi tạo rồi thì chỉ đơn giản thay đổi văn bản của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cho một TextFrameForOverriding mới. |

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe) - Khung văn bản [ITextFrame](../../com.aspose.slides/itextframe)