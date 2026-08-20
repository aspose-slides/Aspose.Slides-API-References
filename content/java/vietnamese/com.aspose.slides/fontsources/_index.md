---
title: FontSources
second_title: Tham chiếu API Aspose.Slides cho Java
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

Cung cấp các nguồn tệp và bộ nhớ cho phông chữ bên ngoài.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontSources()](#FontSources--) | Tạo các tùy chọn phông chữ mặc định mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Thư mục chứa các tệp phông chữ. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Thư mục chứa các tệp phông chữ. |
| [getMemoryFonts()](#getMemoryFonts--) | Một tập hợp các phông chữ được biểu diễn dưới dạng mảng byte. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Một tập hợp các phông chữ được biểu diễn dưới dạng mảng byte. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Tạo các tùy chọn phông chữ mặc định mới.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Thư mục chứa các tệp phông chữ. Tất cả các tệp phông chữ nằm trong các thư mục này sẽ được bao gồm trong tập hợp. Các thư mục được tìm kiếm đệ quy.

**Trả về:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Thư mục chứa các tệp phông chữ. Tất cả các tệp phông chữ nằm trong các thư mục này sẽ được bao gồm trong tập hợp. Các thư mục được tìm kiếm đệ quy.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Một tập hợp các phông chữ được biểu diễn dưới dạng mảng byte.

**Trả về:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Một tập hợp các phông chữ được biểu diễn dưới dạng mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[][] |  |