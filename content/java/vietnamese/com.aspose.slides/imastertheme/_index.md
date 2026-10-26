---
title: IMasterTheme
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một chủ đề chính.
type: docs
url: /vi/com.aspose.slides/imastertheme/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Biểu diễn một chủ đề chính.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Trả về bộ sưu tập các sơ đồ màu bổ sung. |
| [getName()](#getName--) | Trả về tên của một chủ đề. |
| [setName(String value)](#setName-java.lang.String-) | Trả về tên của một chủ đề. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Trả về bộ sưu tập các sơ đồ màu bổ sung. Những sơ đồ này không ảnh hưởng đến giao diện của bản trình chiếu, chúng có thể được chọn làm sơ đồ màu chính cho một slide. Chỉ đọc [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Trả về:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Trả về tên của một chủ đề. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Trả về tên của một chủ đề. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |