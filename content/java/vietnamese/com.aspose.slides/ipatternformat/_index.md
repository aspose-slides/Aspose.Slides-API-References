---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn một mẫu để lấp đầy hình dạng.
type: docs
url: /vi/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Biểu diễn một mẫu để lấp đầy hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Trả về hoặc đặt pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Trả về hoặc đặt pattern style. |
| [getForeColor()](#getForeColor--) | Trả về foreground pattern color. |
| [getBackColor()](#getBackColor--) | Trả về background pattern color. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Tạo hình ảnh ô cho pattern fill với các màu đã chỉ định. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Tạo hình ảnh ô cho pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Trả về hoặc đặt pattern style. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Trả về:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Trả về hoặc đặt pattern style. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Trả về foreground pattern color. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Trả về background pattern color. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```


Tạo hình ảnh ô cho pattern fill với các màu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| background | java.awt.Color | Màu nền java.awt.Color cho pattern. |
| foreground | java.awt.Color | Màu tiền cảnh java.awt.Color cho pattern. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```


Tạo hình ảnh ô cho pattern fill.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.awt.Color | Màu mặc định java.awt.Color, được định nghĩa trong đối tượng StyleEx của ShapeEx. Các màu fill có thể phụ thuộc vào màu này. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.