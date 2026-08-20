---
title: PatternFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một mẫu để tô một hình dạng.
type: docs
url: /vi/com.aspose.slides/patternformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Biểu diễn một mẫu để tô hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Trả về hoặc đặt kiểu mẫu. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Trả về hoặc đặt kiểu mẫu. |
| [getForeColor()](#getForeColor--) | Trả về màu mẫu nền trước. |
| [getBackColor()](#getBackColor--) | Trả về màu mẫu nền sau. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Tạo ảnh gạch lát cho mẫu tô bằng các màu được chỉ định. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Tạo ảnh gạch lát cho mẫu tô. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. long chỉ đọc.

**Trả về:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Trả về hoặc đặt kiểu mẫu. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Trả về:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Trả về hoặc đặt kiểu mẫu. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Trả về màu mẫu nền trước. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Trả về màu mẫu nền sau. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Tạo ảnh gạch lát cho mẫu tô bằng các màu được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| background | java.awt.Color | Màu nền java.awt.Color cho mẫu. |
| foreground | java.awt.Color | Màu trước java.awt.Color cho mẫu. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Tạo ảnh gạch lát cho mẫu tô.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.awt.Color | Màu java.awt.Color mặc định |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).