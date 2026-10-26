---
title: MasterTheme
second_title: Tham khảo API Aspose.Slides cho Java
description: Mô tả một chủ đề chính.
type: docs
url: /vi/com.aspose.slides/mastertheme/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Mô tả một chủ đề chính.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Trả về bảng màu. |
| [getFontScheme()](#getFontScheme--) | Trả về bảng phông chữ. |
| [getFormatScheme()](#getFormatScheme--) | Trả về bảng định dạng hình dạng. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Trả về tập hợp các bảng màu bổ sung. |
| [getName()](#getName--) | Trả về tên của một chủ đề. |
| [setName(String value)](#setName-java.lang.String-) | Trả về tên của một chủ đề. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Trả về bảng màu. Chỉ đọc [IColorScheme](../../com.aspose.slides/icolorscheme).

**Trả về:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Trả về bảng phông chữ. Chỉ đọc [IFontScheme](../../com.aspose.slides/ifontscheme).

**Trả về:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Trả về bảng định dạng hình dạng. Chỉ đọc [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Trả về:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Trả về tập hợp các bảng màu bổ sung. Các bảng màu này không ảnh hưởng đến giao diện của bản trình chiếu, chúng có thể được chọn làm bảng màu chính cho một slide. Chỉ đọc [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Trả về:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Trả về tên của một chủ đề. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Đặt tên cho một chủ đề. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long