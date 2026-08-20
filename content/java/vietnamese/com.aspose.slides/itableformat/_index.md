---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn định dạng của một bảng.
type: docs
url: /vi/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Biểu diễn định dạng của một bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a table fill properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returns a table fill properties object. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Gets or sets the transparency of the fill color. Read/write  float .

**Trả về:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Gets or sets the transparency of the fill color. Read/write  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Gets effective table formatting properties with inheritance and table styles applied.

**Trả về:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Một [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).