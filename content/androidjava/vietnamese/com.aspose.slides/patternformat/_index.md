---
title: PatternFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một mẫu để tô một hình dạng.
type: docs
url: /vi/com.aspose.slides/patternformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Biểu diễn một mẫu để tô hình dạng.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Trả về hoặc thiết lập kiểu mẫu. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Trả về hoặc thiết lập kiểu mẫu. |
| [getForeColor()](#getForeColor--) | Trả về màu mẫu nền trước. |
| [getBackColor()](#getBackColor--) | Trả về màu mẫu nền sau. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Tạo hình ảnh gạch cho việc tô mẫu với các màu được chỉ định. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Tạo hình ảnh gạch cho việc tô mẫu. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Đọc-chỉ long.

**Trả về:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Trả về hoặc thiết lập kiểu mẫu. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Trả về:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Trả về hoặc thiết lập kiểu mẫu. Đọc/ghi [PatternStyle](../../com.aspose.slides/patternstyle).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Trả về màu mẫu nền trước. Đọc-chỉ [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Trả về màu mẫu nền sau. Đọc-chỉ [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Tạo hình ảnh gạch cho việc tô mẫu với các màu được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer nền cho mẫu. |
| foreground | java.lang.Integer | java.lang.Integer nền trước cho mẫu. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Tạo hình ảnh gạch cho việc tô mẫu.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer mặc định |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).