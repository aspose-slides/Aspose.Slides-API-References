---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Giao diện callback dùng để nhận kết quả tìm kiếm văn bản.
type: docs
url: /vi/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Giao diện callback dùng để nhận kết quả tìm kiếm văn bản.
## Phương thức

| Method | Description |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Phương thức callback nhận dữ liệu về văn bản được tìm thấy. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Phương thức callback nhận dữ liệu về văn bản được tìm thấy.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Đối tượng [ITextFrame](../../com.aspose.slides/itextframe) trong đó văn bản được tìm thấy. |
| sourceText | java.lang.String | Văn bản nguồn trong đó văn bản được tìm thấy. |
| foundText | java.lang.String | Văn bản được tìm thấy. |
| textPosition | int | Vị trí của văn bản được tìm thấy. |