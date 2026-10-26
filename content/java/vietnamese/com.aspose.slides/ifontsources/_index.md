---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Cung cấp các nguồn tệp và bộ nhớ cho phông chữ bên ngoài.
type: docs
url: /vi/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Cung cấp các nguồn tệp và bộ nhớ cho phông chữ bên ngoài.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Các thư mục chứa tệp phông chữ. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Các thư mục chứa tệp phông chữ. |
| [getMemoryFonts()](#getMemoryFonts--) | Bộ sưu tập các phông chữ dưới dạng mảng byte. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Bộ sưu tập các phông chữ dưới dạng mảng byte. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Các thư mục chứa tệp phông chữ. Tất cả các tệp phông chữ nằm trong các thư mục này sẽ được đưa vào bộ sưu tập. Các thư mục được tìm kiếm đệ quy.

**Trả về:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Các thư mục chứa tệp phông chữ. Tất cả các tệp phông chữ nằm trong các thư mục này sẽ được đưa vào bộ sưu tập. Các thư mục được tìm kiếm đệ quy.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Bộ sưu tập các phông chữ dưới dạng mảng byte.

**Trả về:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Bộ sưu tập các phông chữ dưới dạng mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[][] |  |