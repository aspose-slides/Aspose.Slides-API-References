---
title: IFillFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các tùy chọn định dạng tô đầy.
type: docs
url: /vi/com.aspose.slides/ifillformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Biểu diễn các tùy chọn định dạng tô đầy.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillType()](#getFillType--) | Trả về hoặc đặt loại tô đầy. |
| [setFillType(byte value)](#setFillType-byte-) | Trả về hoặc đặt loại tô đầy. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu tô. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng tô gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng tô mẫu. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Trả về định dạng tô ảnh. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định xem tô có nên xoay cùng hình hay không. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Xác định xem tô có nên xoay cùng hình hay không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng tô hiệu lực với kế thừa được áp dụng. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Trả về hoặc đặt loại tô đầy. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Trả về hoặc đặt loại tô đầy. Đọc/ghi [FillType](../../com.aspose.slides/filltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Trả về màu tô. Chỉ-đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Trả về định dạng tô gradient. Chỉ-đọc [IGradientFormat](../../com.aspose.slides/igradientformat).

**Trả về:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Trả về định dạng tô mẫu. Chỉ-đọc [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Trả về:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Trả về định dạng tô ảnh. Chỉ-đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Xác định xem tô có nên xoay cùng hình hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Xác định xem tô có nên xoay cùng hình hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng tô hiệu lực với kế thừa được áp dụng.

**Trả về:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).