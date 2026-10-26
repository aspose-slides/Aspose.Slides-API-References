---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Lưu trữ các phông chữ được xác định trong chủ đề.
type: docs
url: /vi/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Lưu trữ các phông chữ được xác định trong chủ đề.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getMinor()](#getMinor--) | Trả về bộ sưu tập phông chữ cho phần "body" của slide. |
| [getMajor()](#getMajor--) | Trả về bộ sưu tập phông chữ cho phần "heading" của slide. |
| [getName()](#getName--) | Trả về tên của font scheme. |
| [setName(String value)](#setName-java.lang.String-) | Trả về tên của font scheme. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Trả về bộ sưu tập phông chữ cho phần "body" của slide. Chỉ đọc [IFonts](../../com.aspose.slides/ifonts).

**Giá trị trả về:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Trả về bộ sưu tập phông chữ cho phần "heading" của slide. Chỉ đọc [IFonts](../../com.aspose.slides/ifonts).

**Giá trị trả về:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Trả về tên của font scheme. Đọc/ghi String.

**Giá trị trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Trả về tên của font scheme. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |