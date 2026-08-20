---
title: LineFillFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các thuộc tính của việc tô màu các đường.
type: docs
url: /vi/com.aspose.slides/linefillformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Đại diện cho các thuộc tính của việc tô màu các đường.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Trả về hoặc đặt kiểu tô màu. |
| [setFillType(byte value)](#setFillType-byte-) | Trả về hoặc đặt kiểu tô màu. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định xem việc tô màu có nên được xoay cùng hình dạng hay không. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Xác định xem việc tô màu có nên được xoay cùng hình dạng hay không. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu của tô đồng nhất. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng tô gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng tô mẫu. |
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


Trả về hoặc đặt kiểu tô màu. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Trả về hoặc đặt kiểu tô màu. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Xác định xem việc tô màu có nên được xoay cùng hình dạng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Xác định xem việc tô màu có nên được xoay cùng hình dạng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Trả về màu của tô đồng nhất. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Trả về định dạng tô gradient. Chỉ đọc [IGradientFormat](../../com.aspose.slides/igradientformat).

**Trả về:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Trả về định dạng tô mẫu. Chỉ đọc [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Trả về:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)