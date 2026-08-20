---
title: ILineFillFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các thuộc tính của việc lấp đầy các đường.
type: docs
url: /vi/com.aspose.slides/ilinefillformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Đại diện cho các thuộc tính của việc lấp đầy các đường.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillType()](#getFillType--) | Trả về hoặc thiết lập kiểu lấp đầy. |
| [setFillType(byte value)](#setFillType-byte-) | Trả về hoặc thiết lập kiểu lấp đầy. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu của một lấp đầy đặc. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng lấp đầy gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng lấp đầy mẫu. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định liệu lấp đầy có nên xoay cùng hình dạng hay không. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Xác định liệu lấp đầy có nên xoay cùng hình dạng hay không. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Trả về hoặc thiết lập kiểu lấp đầy. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Trả về hoặc thiết lập kiểu lấp đầy. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Trả về màu của một lấp đầy đặc. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Trả về định dạng lấp đầy gradient. Chỉ đọc [IGradientFormat](../../com.aspose.slides/igradientformat).

**Trả về:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Trả về định dạng lấp đầy mẫu. Chỉ đọc [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Trả về:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Xác định liệu lấp đầy có nên xoay cùng hình dạng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Xác định liệu lấp đầy có nên xoay cùng hình dạng hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |