---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Đối tượng bất biến chứa các thuộc tính điền dòng hiệu quả.
type: docs
url: /vi/com.aspose.slides/ilinefillformateffectivedata/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Đối tượng bất biến chứa các thuộc tính điền dòng hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillType()](#getFillType--) | Trả về loại tô. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu của tô đặc. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng tô gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng tô mẫu. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định xem tô có nên xoay cùng hình hay không. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Trả về loại tô. Chỉ đọc [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Trả về màu của tô đặc. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Trả về định dạng tô gradient. Chỉ đọc [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Trả về:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Trả về định dạng tô mẫu. Chỉ đọc [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Trả về:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Xác định xem tô có nên xoay cùng hình hay không. Chỉ đọc boolean.

**Trả về:**
boolean