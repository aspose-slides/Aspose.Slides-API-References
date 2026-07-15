---
title: LineFillFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho các thuộc tính của việc tô màu cho các đường.
type: docs
url: /vi/com.aspose.slides/linefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Đại diện cho các thuộc tính của việc tô màu cho các đường.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Trả về hoặc đặt kiểu đổ màu. |
| [setFillType(byte value)](#setFillType-byte-) | Trả về hoặc đặt kiểu đổ màu. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định xem việc đổ màu có nên xoay cùng hình dạng hay không. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Xác định xem việc đổ màu có nên xoay cùng hình dạng hay không. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu của đổ màu đặc. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng đổ màu gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng đổ màu hoa văn. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Trả về hoặc đặt kiểu đổ màu. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Trả về hoặc đặt kiểu đổ màu. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Xác định xem việc đổ màu có nên xoay cùng hình dạng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Xác định xem việc đổ màu có nên xoay cùng hình dạng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Trả về màu của đổ màu đặc. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Trả về định dạng đổ màu gradient. Chỉ đọc [IGradientFormat](../../com.aspose.slides/igradientformat).

**Trả về:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Trả về định dạng đổ màu hoa văn. Chỉ đọc [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Trả về:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)