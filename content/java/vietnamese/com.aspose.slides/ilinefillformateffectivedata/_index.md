---
title: ILineFillFormatEffectiveData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đối tượng bất biến chứa các thuộc tính điền dòng hiệu quả.
type: docs
url: /vi/com.aspose.slides/ilinefillformateffectivedata/
---
**Tất cả các giao diện được triển khai:**
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
| [getFillType()](#getFillType--) | Trả về loại tô màu. |
| [getSolidFillColor()](#getSolidFillColor--) | Trả về màu của tô màu đặc. |
| [getGradientFormat()](#getGradientFormat--) | Trả về định dạng tô màu gradient. |
| [getPatternFormat()](#getPatternFormat--) | Trả về định dạng tô màu mẫu. |
| [getRotateWithShape()](#getRotateWithShape--) | Xác định liệu tô màu có nên xoay cùng hình dạng hay không. |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Trả về loại tô màu. Chỉ đọc [FillType](../../com.aspose.slides/filltype).

**Trả về:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

Trả về màu của tô màu đặc. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Trả về định dạng tô màu gradient. Chỉ đọc [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Trả về:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Trả về định dạng tô màu mẫu. Chỉ đọc [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Trả về:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Xác định liệu tô màu có nên xoay cùng hình dạng hay không. Chỉ đọc boolean.

**Trả về:**
boolean