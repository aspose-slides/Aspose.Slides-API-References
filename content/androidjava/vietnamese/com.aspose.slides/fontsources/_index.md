---
title: FontSources
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp nguồn tệp và bộ nhớ cho phông chữ bên ngoài.
type: docs
url: /vi/com.aspose.slides/fontsources/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Cung cấp nguồn tệp và bộ nhớ cho phông chữ bên ngoài.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontSources()](#FontSources--) | Tạo tùy chọn phông chữ mặc định mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Thư mục chứa tệp phông chữ. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Thư mục chứa tệp phông chữ. |
| [getMemoryFonts()](#getMemoryFonts--) | Một bộ sưu tập các phông chữ được biểu diễn dưới dạng mảng byte. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Một bộ sưu tập các phông chữ được biểu diễn dưới dạng mảng byte. |
### FontSources() {#FontSources--}
```
public FontSources()
```

Tạo tùy chọn phông chữ mặc định mới.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

Thư mục chứa tệp phông chữ. Tất cả các tệp phông chữ nằm trong các thư mục này sẽ được bao gồm trong bộ sưu tập. Các thư mục được tìm kiếm đệ quy.

**Trả về:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

Thư mục chứa tệp phông chữ. Tất cả các tệp phông chữ nằm trong các thư mục này sẽ được bao gồm trong bộ sưu tập. Các thư mục được tìm kiếm đệ quy.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

Một bộ sưu tập các phông chữ được biểu diễn dưới dạng mảng byte.

**Trả về:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

Một bộ sưu tập các phông chữ được biểu diễn dưới dạng mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[][] |  |