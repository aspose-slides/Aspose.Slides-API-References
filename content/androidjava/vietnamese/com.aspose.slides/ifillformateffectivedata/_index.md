---
title: IFillFormatEffectiveData
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đối tượng bất biến chứa các thuộc tính định dạng tô đầy hiệu lực.
type: docs
url: /vi/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Đối tượng bất biến chứa các thuộc tính định dạng tô đầy hiệu lực.

--------------------

Giao diện này được sử dụng cùng với giao diện [IFillFormat](../../com.aspose.slides/ifillformat) để trả về các giá trị định dạng hiệu lực với việc kế thừa được áp dụng.
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [getFillType()](#getFillType--) | Trả về loại tô đầy. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu tô đầy. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Lấy màu tô đầy được định nghĩa bởi một bảng màu. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng tô đầy gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng tô đầy mẫu. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Trả về định dạng tô đầy hình ảnh. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định xem tô đầy có nên quay cùng hình dạng hay không. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Trả về loại tô đầy. Chỉ đọc [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Trả về màu tô đầy. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Lấy màu tô đầy được định nghĩa bởi một bảng màu. Giá trị [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) cho biết SolidFillColor (\#getSolidFillColor.getSolidFillColor) không phải là một màu trong bảng màu. Chỉ đọc [SchemeColor](../../com.aspose.slides/schemecolor).

**Trả về:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Trả về định dạng tô đầy gradient. Chỉ đọc [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Trả về:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Trả về định dạng tô đầy mẫu. Chỉ đọc [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Trả về:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Trả về định dạng tô đầy hình ảnh. Chỉ đọc [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Trả về:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Xác định xem tô đầy có nên quay cùng hình dạng hay không. Chỉ đọc boolean.

**Trả về:**
boolean