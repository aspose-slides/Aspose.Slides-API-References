---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /vi/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Represents a pattern to fill a shape.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Trả về hoặc thiết lập kiểu mẫu. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Trả về:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Trả về hoặc thiết lập kiểu mẫu. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Trả về màu mẫu nền trước. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Trả về màu mẫu nền sau. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Tạo một ảnh tile cho việc lấp mẫu với các màu được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| background | java.lang.Integer | The background java.lang.Integer for the pattern. |
| foreground | java.lang.Integer | The foreground java.lang.Integer for the pattern. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Tạo một ảnh tile cho việc lấp mẫu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.lang.Integer | The default java.lang.Integer, defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.